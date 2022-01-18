# servicenow-auto-logger
* This project helps you automate the login to your servicenow PDI there removing the requirement to manually login into your instance every 10 days before servicenow can reclaim it.
* You need to create an account on https://www.pythonanywhere.com/ and follow the steps to clone this repo.
* Install all the requirements using the bash console.
* In case you are facing issues with chromedriver , You can download the suitable version of chromedriver from https://chromedriver.storage.googleapis.com/. I have used 90.0.4430.24/ chromedriver_linux64.zip.
* Create a task to run the main.py file everyday at a particular time.
* Check the last_login_time of the user you have used. last_login_time is a property of sys_user record.

# issues-faced-while-automating
* CHROMEDRIVER file has insufficient permission : Run this command in bash cosole (chmod 755 "/home/imlucifer/servicenow-auto-login/chromedriver)
* Version errors : As i was using python3.9 interpreter i upgraded my selenium using this command (pip3.9 install --user --upgrade selenium)

## Python Anywhere requires you to login every 30 days in order to continue your task on a free account tier. So make sure to login every 30 days to your python anywhere account.
