# Project-4
Assignment 4
#Enter the price of the House i wish to Buy
price= input("Enter the House Price: ")
#Enter the Down Payment
down_payment = input("Down Payment: ")
#Enter the first name
first_name = input("Enter first name: ")
#Enter the last name
last_name = input("Enter last name: ")

fullnames = (first_name + " " + last_name)

#Enter the Phone No
phone_no=input("Enter the Phone No: ")

#Enter the email
email=input("Enter the Email Address: ")

#Enter the mailings
postal_address =input("Enter the Postal Address: ")
zip_code = input("Enter the Zip Code: ")
city=input("Enter the City: ")

#Qualify for loans with the best interest rates
credit_score=input("Enter Credit Score:")
print("Credit Score: " + credit_score)
ifint(credit_score)>=780 & 850:
down_payment = (0.0 * int(price))
print("Excellent Credit")
print(f"Zero Down Payment:{down_payment}")
elifint(credit_score)>=720 & 739:
print("Very Good")
down_payment = (0.3 * int(price))
print(f"Down Payment:{down_payment}")
elifint(credit_score)>=680 & 719:
print("Average")
down_payment = (0.6 * int(price))
print(f"Down Payment:{down_payment}")
elifint(credit_score)>=680 & 679:
print("Below Average")
down_payment = (0.18 * int(price))
print(f"Down Payment:{down_payment}")
Below_Average = input()
elifint(credit_score)>=580 & 619:
print("Below Average")
down_payment = (0.20 * int(price))
print(f"Down Payment:{down_payment}")
poor_credit_score = input()
else:
int(credit_score) <=520
print("Poor Credit Score")
down_payment = (0.25 * int(price))

print()
print("Fullnames: " + fullnames)
print("Postal Address: " + postal_address)
print("City:" + city)
print("Zip Code: " + zip_code)
print("New House Price: " + price)
print("Email: " + email)
print("Down Payment",down_payment)
print("Credit Status: " " " + credit_score)
print("Phone Number: " + str(phone_no))

