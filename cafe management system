#CAFE MANAGEMENT SYSTEM
print("Welcome to PYTHON restaurant, Here's the menu:")
a="Corn pizza:Rs-40"
ab="Moserilla cheese pizza:Rs-50"
ac="Crispy twist pizza:Rs-70"
b="Masala pasta:Rs-50"
ba="White saus pasta:Rs-70"
c="Vegetable salad:Rs-70"
ca="Fruit salad:Rs-90"
d="Coffee:Rs-80"
e="Aloo tikki burger:Rs-60"
ea="Paneer swish burger:Rs-80"
eb="Cheese burger:Rs-100"
ec="Chicken burger:Rs-160"
a1=40
ab1=50
ac1=70
b1=50
ba1=70
c1=70
ca1=90
d1=80
e1=60
ea1=80
eb1=100
ec1=160
tot_bill=0
print("PIZZA SECTION")
print("1-",a)
print("2-",ab)
print("3-",ac)
print("PASTA SECTION")
print("4-",b)
print("5-",ba)
print("SALAD SECTION")
print("6-",c)
print("7-",ca)
print("COFFEE SECTION")
print("8-",d)
print("BURGER SECTION")
print("9-",e)
print("10-",ea)
print("11-",eb)
print("12-",ec)
h=0
while h<2:
    choise=int(input("enter your choise:(1/2/3/4/5.....12):"))
    if choise==1:
        size=(input("Size?[small/regular/large]:"))
        pizza1_quan=int(input("quanty:(1/2/3....)"))
        print("your Corn pizza order has been placed,Rs-",a1*pizza1_quan)
        tot_bill+=a1*pizza1_quan
    elif choise==2:
        size = (input("Size?[small/regular/large]:"))
        pizza2_quan = int(input("quanty:(1/2/3....)"))
        print("your Moserilla cheese pizza order has been placed,Rs-",ab1*pizza2_quan)
        tot_bill+=ab1*pizza2_quan
    elif choise==3:
        size = (input("Size?[small/regular/large]:"))
        pizza3_quan = int(input("quanty:(1/2/3....)"))
        print("your Crispy twist pizza order has been placed,Rs-",ac1*pizza3_quan)
        tot_bill+=ac1*pizza3_quan
    elif choise==4:
        size = (input("Size?[small/regular/large]:"))
        pasta_quan = int(input("quanty:(1/2/3....)"))
        print("your Masala pasta order has been placed,Rs-",b1*pasta_quan)
        tot_bill+=b1*pasta_quan
    elif choise==5:
        size = (input("Size?[small/regular/large]:"))
        pasta2_quan = int(input("quanty:(1/2/3....)"))
        print("your White saus pasta order has been placed,Rs-",ba1*pasta2_quan)
        tot_bill+=ba1*pasta2_quan
    elif choise==6:
        size = (input("Size?[small/regular/large]:"))
        salad_quan = int(input("quanty:(1/2/3....)"))
        print("your Vegetable salad order has been placed,Rs-",c1*salad_quan)
        tot_bill+=c1*salad_quan
    elif choise==7:
        size = (input("Size?[small/regular/large]:"))
        salad2_quan = int(input("quanty:(1/2/3....)"))
        print("your Fruit salad order has been placed,Rs-",ca1*salad2_quan)
        tot_bill+=ca1*salad2_quan
    elif choise==8:
        size = (input("Size?[small/regular/large]:"))
        coffee_quan = int(input("quanty:(1/2/3....)"))
        print("your Coffee order has been placed,Rs-",d1*coffee_quan)
        tot_bill+=d1*coffee_quan
    elif choise==9:
        size = (input("Size?[small/regular/large]:"))
        burger_quan = int(input("quanty:(1/2/3....)"))
        print("your Aloo tikki burger order has been placed,Rs-",e1*burger_quan)
        tot_bill+=e1*burger_quan
    elif choise==10:
        size = (input("Size?[small/regular/large]:"))
        burger2_quan = int(input("quanty:(1/2/3....)"))
        print("your Paneer swish burger order has been placed,Rs-",ea1*burger2_quan)
        tot_bill+=ea1*burger2_quan
    elif choise==11:
        size = (input("Size?[small/regular/large]:"))
        burger3_quan = int(input("quanty:(1/2/3....)"))
        print("your Cheese burger order has been placed,Rs-",eb1*burger3_quan)
        tot_bill+=eb1*burger3_quan
    elif choise==12:
        size = (input("Size?[small/regular/large]:"))
        burger4_quan = int(input("quanty:(1/2/3....)"))
        print("your Chicken burger order has been placed,Rs-",ec1*burger4_quan)
        tot_bill+=ec1*burger4_quan
    g=input("Want to order anything else:(yes=y/no=n):")
    if g=="y":
        continue
    elif g=="n":
        break
print("your total bill is: Rs",tot_bill)
input("Do you want parsel of this order?(yes/no):")
delevry=input("Do you want home delivery?(yes=y/no=n)")
if delevry=="y":
    add=input("enter your address:")
    print("Thankyou we will deliver your order at",add)
else:
    print("OK")
print("PAYMENT")
pay=input("How would you like to do the payment?(cash=c/online=o):")
if pay=="c":
    print("**You may deposite Rs-",tot_bill,"on the counter**")
    int(input("How much would you rate us:(*1/*2/*3/*4/*5):"))
    print("**Thankyou for visiting, Visit again**")
elif pay=="o":
    int(input("enter account number:"))
    print("proceed to pay Rs-",tot_bill)
    int(input("enter your mobile number:"))
    print("your payment of Rs-",tot_bill," is successful")
    int(input("How much would you rate us:(*1/*2/*3/*4/*5):"))
    print("**Thankyou for visiting, visit again")

