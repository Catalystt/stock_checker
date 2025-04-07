# get_my_deck
A simple scraper which checks the Steam Deck Refurb page for stock (64gb) since there doesn't seem to be any for refurbs out there and definitely no official way of doing this.
Other options for webscrapers were paid.

The parts that need editing are in the ## comments.

Requirements: 
Python - Latest is fine
Selenium Chrome Drivers for Python via PIP
https://tecadmin.net/setup-selenium-with-python-on-ubuntu-debian/

Free Twilio Account and installation via PIP
pip install twilio 

Pycharm(or another IDE) - optional
If you require a different model size, then a tiny bit of googling/coding to change the text params to capture the different size model

To Run:

Command line - python get_my_deck.py
