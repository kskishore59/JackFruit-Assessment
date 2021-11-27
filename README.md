# JackFruit-Assessment

Assignment for Jackfruit

Task: Design a basic responsive web app that takes a few input parameters from the user and calculates the user’s taxable income

Steps:

(Words in bold are just to indicate the different variables. You may use any nomenclature that you feel comfortable with)

Any individual’s salary consists of different components: Basic, LTA, HRA, Food Allowance etc. Ask the user to input these 4 parameters (Bas, LTA, HRA, FA)

Ask the user to input the following:
Investments under section 80C (Inv)
Actual Rent paid by user (Rent)
User stays in Metro/Non metro city (CityType)
Mediclaim policy premium paid by user (Med)

Compute the applicable HRA (called AppHRA) as follows:
If user lives in metro city, AppHRA is calculated as minimum of the below 3:
50% of Bas
Rent - 10% of Bas
HRA
If user lives in non-metro city, AppHRA is calculated as minimum of the below 3:
40% of Bas
Rent - 10% of Bas
HRA

Store all entered values in db and display values to user in a popup before he/she submits

After user confirms and submits data, compute Taxable Income (TaxInc) as follows:
TaxInc = (Bas + LTA + HRA + FA) - AppHRA - Inv - Med

Display Taxable Income to the user

Basic login functionality is required before user inputs data

UI should be clean and aesthetically pleasing, as far as possible. Use of some animations in the front end will be a plus point for the candidate

It will be better if the candidate can deploy it on the server. If not, then file can be shared by email.
