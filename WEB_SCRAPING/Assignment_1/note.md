steps:

from bs4 import BeautifulSoup
import requests
page = requests.get('https://internshala.com/fresher-jobs')
print(page)
soup = BeautifulSoup(page.content)



# a.isdigit() this return only digit

