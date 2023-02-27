import requests

url = "https://api.short.io/links/LINK_ID"

headers = {'authorization': 'APIKEY'}

response = requests.request("DELETE", url, headers=headers)

print(response.text)
