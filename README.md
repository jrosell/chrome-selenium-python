# chrome-selenium-python
### Use Google Chrome from your python scrips using WebDriver for navigating to web pages, user input, JavaScript execution, and more. 

## Linux

You can use selenium on Ubuntu with Python3 by following this steps:

1. Clone the project (change myproject to whatever your want)
git clone https://github.com/jrosell/chrome-selenium-python myproject
cd myproject

2. Install pip for python3 using:
sudo apt-get install python3-pip 

3. Install selenium for python3 using:
sudo python3 -m pip install -U selenium 

4. If you need to update current chromedriver, download it from https://sites.google.com/a/chromium.org/chromedriver/downloads and extract it there.
Currently using ChromeDriver 78.0.3904.70

5. Reference chromedriver from your scripts.
Change webdriver.Chrome call with your chromedriver path on run.py
Having /home/jordi/chrome-selenium-python path, I'm using /home/jordi/chrome-selenium-pythonchromedriver

6. Run it
python3 run.py

7. Have fun!
Copy run.py script and edit your new scripts. 

## Open for collaborations
You can do pull resquests or open issues if you want to help.
