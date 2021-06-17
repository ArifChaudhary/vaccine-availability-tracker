# vaccine-availability-tracker

Vaccine checker for India using pincode
Vaccine checker is a simple tool for tracking the availability of Covid vaccines in any state in India by pincode. It uses the api from COWIN site to monitor for vaccine availability.

Features
Check availability of vaccine by providing pincodeof your area
Run in the terminal and monitor the vaccine availability

Set Up
Vaccine-checker requires python3 to run

Project dependencies can be installed using the following command:

pip install -r requirements.txt

Using pincode.
Set your area pincode in config file file as shown below. Find pincode of your area here

area_info:
# [edit] enter your pincode 
  __pincode : "<pincode>"
Edit vaccineChecker file and set

query_type = "pincode"
Run

python3 vaccine_availability.py
Then it'll search for vaccine availability in your area.

query_type = "pincode"
Run the script after setting the values

python3 vaccine_availability.py
It'll search for availibility of vaccine centers in that area.

Development
Want to contribute? Great! Feel free to raise a pull request 🤗
