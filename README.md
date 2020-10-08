# scrapping-with-python
Automote with ease the long process of browsing.
Import bs4 as bs
Import urllib.request
Page = urllib.request.urlopen('https://www.google.com')
Soup = bs.BeautifulSoup(page,'lxml')
