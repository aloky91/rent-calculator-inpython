# rent-calculator-inpython
##inputs we need from the user
# Total Rent
# Total food ordered for snacking
# Total grocery spend
#Electricity units spend
# charge per unit
# Persons living in room/flat

## output
# Total amount you've to pay

rent = int(input("Enter your hostel/ flat rent ="))
food = int(input(" Enter the amount of food ordered = "))
electricity_spend = int(input("Enetr the total of electricity spend = " ))
charge_per_unit = int(input("Enter the charge per unit = "))
grocery_spend = int(input("Enter the total grocery spend = "))
persons =int(input("Enter the number of persons living in the room/flat = "))

total_bill =electricity_spend * charge_per_units

output = (food + grocery_spend + total_bill) //persons

print("Each person will pay = ",output)
