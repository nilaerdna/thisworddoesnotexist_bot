# ThisWordDoesNotExist_Bot
Python script/bot to automatically scrape from data from [thisworddoesnotexist.com](https://www.thisworddoesnotexist.com/) made by [Thomas Dimson](https://github.com/turtlesoupy) and upload them to Instagram.
## Getting Started
There are two easy ways to use the script.
 - Clone project then input your instagram data and run "bot.py". Running the script will cause the script to act like a bot which periodically fetches the data.
```
usrnm, pswrd  =  "USERNAME HERE", "PASSWORD HERE"
```
 - Clone project and edit "bot.py" to your liking. Removing the scheduler will cause the script to no longer act like a bot.
### Prerequisites
The "requirements.txt" file contains any Python dependencies. You can install them by running this command:
```
pip3 install -r requirements.txt
```
## Built With
- [Selenium](https://www.selenium.dev/documentation/en/) - Browser Automation.
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - HTML documents analysis.
- [PIL](https://pillow.readthedocs.io/en/stable/) - Python Image Library.
- [Instabot](https://github.com/instagrambot/instabot) - Instagram Python API.
- [Schedule](https://schedule.readthedocs.io/en/stable/) - Python job scheduling for humans.
### Creators
[Andrea Lin](https://github.com/nilaerdna/) & [Mattia Ferrari](https://github.com/IlSassone)
