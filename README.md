#  Automated Appointment Booking (calmark website)
This Python script uses Selenium WebDriver to automate the process of booking an appointment on the Calmark.co.il website.
It simulates a real user logging in and selecting a service, provider, and available appointment date.

 Features:
Launches a Chrome browser and navigates to the Calmark website

Logs in using a phone number and password

Waits for dynamic elements to load using smart waits (WebDriverWait)

Selects a specific service and employee

Finds and clicks the latest available appointment date on the calendar

Uses JavaScript actions to scroll and interact with elements when needed

Handles potential exceptions such as timeouts or blocked clicks

 Used:
Python

Selenium WebDriver

ChromeDriver

 Notes:
Replace "Your phone number" and "Your password" with real credentials before running

Make sure you have Chrome and the corresponding version of ChromeDriver installed

You may need to adjust timeouts or XPaths if the website structure changes
