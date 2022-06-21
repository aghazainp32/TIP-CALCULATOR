# TIP-CALCULATOR
Welcome to tip calculator
print("welcome to the tip calculator")
bill=float(input("what was the total bill? $"))
tip=int(input("how much tip would you like to give? 10, 12, or 15? "))
person=int(input("how many people to split the bill?"))
tip_with_bill=tip/100*bill
total_bill=bill+tip_with_bill
share_per_person=total_bill/person
final_amount="{:.2f}".format(share_per_person)
print(share_per_person)
