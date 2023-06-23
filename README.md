import requests

url = "https://pickleballopinion.com/pickleball-court-dimensions/"

# Send a GET request to the URL
response = requests.get(url)

# Check if the request was successful (status code 200)
if response.status_code == 200:
    # Print the content of the webpage
    print(response.content)
else:
    # Print an error message if the request failed
    print("Error: Failed to retrieve the webpage")
# JNO
