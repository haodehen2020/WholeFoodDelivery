# WholeFoodDelivery
# Whole Foods and Amazon Fresh Delivery Slot Automated Script

Yes, amid COVID-19 trying to get Whole Foods and Amazon Fresh delivery slots can get cumbersome. To free you off the constant hassle of checking for slots (and almost never finding one), this automated script can notify you (yes notifies you verbally, so you can go about your tasks) of when new delivery slots open.


## Usage:
Supports **MacOS, Linux, and Windows**.

Note, use the ```whole_foods_delivery_windows.py``` for Windows. Also, only for this OS, you'll have to install an additional package ```winsound```

The script works on **Chrome** (```whole_foods_delivery_slot_chrome.py``` for Whole Foods) (```amazon_fresh_delivery_slot_chrome.py``` for Amazon Fresh) and **FireFox** (```whole_foods_delivery_slot_firefox.py```) for now. 
It initializes a  webdriver, for which if you don't have one install it from: https://chromedriver.chromium.org/ for Chrome and https://github.com/mozilla/geckodriver/releases for FireFox.

You'll have to update the path of the this installed webdriver under: ```python driver = webdriver.Chrome()``` if its not the default location your OS needs. Similarly, for FireFox ```python driver = webdriver.Firefox(executable_path="<your-webdriver-path>")```

Script was written on Python 2.7.10




_The script works after you have added all the items to your cart! Note, have your cart ready before running this script! Also, please don't let your computer sleep. Let your computer do the work, while you sleep_



### After you clone the project:
_Walkthrough for Chrome for Whole Foods, follow same steps if running on FireFox with the FireFox script_

1. Run the requirements.txt (```$ pip install -r requirements.txt```)
2. Run whole_foods_delivery_slot_chrome.py (``` $ python whole_foods_delivery_slot_chrome.py```)
3. The first time you run this script, Whole Foods cart will ask you to login. After you login, go to the "Shipping and Payment" window. Its titled: _Schedule your order_. Leave the script running.
4. Get a nice warm Tea, browse reddit, do something on Xbox, etc.
5. Once a slot opens the script will verbally notify you of an open slot.
6. Proceed to checkout once you select a time slot. Stay Safe!