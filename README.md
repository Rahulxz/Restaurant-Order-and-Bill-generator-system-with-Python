# Order and Bill Generator
import pandas as pd

import random as rd

import pyqrcode

import png

from pyqrcode import QRCode

bill=0

result=0

gst=0

total=0

def cost(x,a,b,c,d,e,f):

    print()
    print("BILL")
    print()
    if (a==1):
        c=10
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
        
        
        
    elif (a==2):
        c=10
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==3):
        c=20
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==4):
        c=90
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==5):
        c=110
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==6):
        c=90
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==7):
        c=110
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==8):
        c=140
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==9):
        c=130
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==10):
        c=180
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==11):
        c=70
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==12):
        c=15
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==13):
        c=30
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    elif (a==14):
        c=130
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
    else:
        c=140
        f=c*b
        d=(b*c*18)/100
        e=(c*b)+d
        ledger={
            'Name':[x],
            'Order No':[a],
            'Quantity':[b],
            'Total':[f],
            'Gst18%':[d],
            'Billing Amount':[e]
            }
        df=pd.DataFrame(ledger)
        print(df)
        print("Thank You for Ordering")
        
name=input("Enter your name:-" )

while (name==""):

    print()

    print("please enter a valid name")
    
    print()
    
    name=input("Enter your name:-" )

else:

    print()
    
    print("Welcome to THE RESTAURANT",name)

print()

b=str(input("Enter your Phone number or Email Id for OTP verification: "))

while (b==""):

    print()
    
    print("please enter a valid number or email")
    
    print()
    
    b=str(input("Enter your Phone number or Email Id for OTP verification: "))
    
else:
  
    print()

print()

a=str(rd.randint(0,9))+str(rd.randint(0,9))+str(rd.randint(0,9))+str(rd.randint(0,9))

print(a)

print()

b=str(input("Enter the Otp:- "))

while (a!=b):

    print()
    
    print("Incorrect Otp ")
    
    print()
    
    a=str(rd.randint(0,9))+str(rd.randint(0,9))+str(rd.randint(0,9))+str(rd.randint(0,9))
    
    print(a)
    
    print()
    
    b=str(input("Enter the Otp:- "))
        

else:

    print()
    
    print("Otp verified Successfully")

print()

print("Scan the QRCode from All files for opening the Menu please.")

print()

print("The File name is restaurant_menu.")

data="""Menu

Choose our Delicacies which Delight you.

Enter the number assigned to the Dish as for you to order it.

1- Tea               Rs-10

2-Coffee            Rs-10

3-Softdrinks     Rs-20

4-Veg Thali      Rs-90

5-Non-Veg Thali  Rs-110

6-Dessert        Rs-90

7-Paneer Chilli   Rs-110

8-Chicken Chilli Rs-140

9-Paneer Gravy   Rs-130

10-Chicken Gravy  Rs-180

11-Rice Plate     Rs-70

12- Roti(1)        Rs-15

13-Naan           Rs-30

14-Fish Fry       Rs-130

15-Prawns Fry     Rs-140

"""
url=pyqrcode.create(data)

url.svg("restaurant_menu.svg",scale=8)

url.png("restaurant_menu.png",scale=6)

print()

ask=input("Have you decided what to order(y/n):")

while ask=='n':

    print()
    
    print("Go through the Menu again")
    
    print()
    
    ask=input("Have you decided what to order(y/n):")

else:

    print()

print()

print("Order from 1 - 15 delicious dishes from the menu and enjoy")

print()

order=int(input("Enter the Number assigned to the dish for your order: "))
         
while (order>15)or(order<=0):

    print()
    
    print("Invalid order enter the correct number")
    
    print()
    
    order=int(input("Enter the Number assigned to the dish for your order: "))
    
quants=int(input("Enter the desired amount you want to order: "))

print()

confirmation=(input("Do you Confirm yor Order(y/n): "))

Print()

while confirmation=='n':

    print()
    
    print("Confirmation Cancelled reorder")
    
    print()
    
    order=int(input("Enter the Number assigned to the dish for your order: "))
    
    print()
    
    while (order>15)or(order<=0):
    
        print()
        
        print("Invalid order enter the correct number")
        
        print()
        
        order=int(input("Enter the Number assigned to the dish for your order: "))
    
    print()
    
    quants=int(input("Enter the desired amount you want to order: "))
    
    print()
    
    confirmation=(input("Do you Confirm yor Order(y/n): "))

print()

cost(name,order,quants,result,gst,bill,total)

    

    
    
    
