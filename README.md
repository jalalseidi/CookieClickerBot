# Cookie Clicker Bot - Selenium Automation

This project is a Python automation bot built using Selenium to play the classic [Cookie Clicker game](http://orteil.dashnet.org/experiments/cookie/).

## Overview
The bot continuously clicks the main cookie and automatically purchases the most expensive available upgrade every 5 seconds. After 5 minutes, it stops and displays the cookies per second rate.

## Features
- Repeatedly clicks the cookie to accumulate cookies
- Every 5 seconds, checks for and purchases the most expensive affordable upgrade
- Automatically stops after 5 minutes
- Outputs final "cookies per second" rate

## Requirements
- Python 3.x
- Google Chrome browser
- [ChromeDriver](https://sites.google.com/chromium.org/driver/) (must match your browser version)
- Selenium package (install using `pip install selenium`)

## How to Run
1. Install Python, Chrome, ChromeDriver, and Selenium.
2. Save the script in a `.py` file.
3. Run the script using:

```bash
python main.py
```

The Chrome browser will open, and the bot will begin clicking and buying upgrades.

## Code Highlights
- Uses Selenium WebDriver to interact with the webpage
- Uses `time.time()` to manage the 5-second and 5-minute timers
- Parses element text to get cookie counts and upgrade prices

## Possible Improvements
- Buy all affordable upgrades, not just the most expensive
- Optimize clicking speed
- Track total upgrades and efficiency
- Add GUI or logs for real-time feedback

## Disclaimer
This bot is for educational purposes only and should not be used to manipulate online services in violation of their terms of service.

## Author
Jalal – Python Developer & Automation Enthusiast

