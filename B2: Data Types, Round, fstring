"""You are working at the dealsership of Alpha Motors. A customer walked in and wanted to know the total Sale Price of a particular Car model and the Monthly Payment for 36 months option. You are going to use python to calcaute sale price with tax and monthly payament inlcuding finance charges"""

print ("Welcome to Alpha Motors!")
#Enter Sale Price
Sales_Price = int(input("What is the sale price of a car?"))
#Enter Sale Tax %
Sales_Tax = int(input("What is the sales tax?"))
#Sales Price + Sale Tax
Total_Sales_Price = Sales_Tax / 100 * Sales_Price + Sales_Price
#fstring
print(f"Total Sales Price of the car including sales tax is {Total_Sales_Price}")

#Enter finance duraton (Customer asked for 36 months)
Finance_Duration = int(input("What is the finance duration?"))
#Enter finance charges (It is $3000 for 36 months)
Finance_Charges = int(input("What are the finance charges?"))
#Sale Price + Finance Charge
Total_Sales_Price_with_Finance_Charges = Total_Sales_Price + Finance_Charges
#Monthly Payemnt Calcuation
Monthly_Payment = round(Total_Sales_Price_with_Finance_Charges / Finance_Duration,2)
#fstring
print(f"The Monthly payment of the car will be {Monthly_Payment}")
#fstring
print(f"The Total Sales Price of the car including tax is {Total_Sales_Price} and Montly payment will be {Monthly_Payment} for 36 months.")
