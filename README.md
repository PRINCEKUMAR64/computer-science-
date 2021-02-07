print("S_NO.          {CALCULATION}")
print("\n1--------------area of square")
print("2--------------area of rectangle")
print("3--------------area of triangle")
print("4--------------area of circle")
print("5--------------Total surface area of cuboid")
print("6--------------Total surface area of cube")
print("7--------------Total surface area of cylinder")
print("8--------------Total surface area of sphere")
print("9--------------Total surface area of hemisprere")
print("10-------------Total surface area of frustum")
z=int(input('SELECT S_NO. :'))
if(z==1):
    s=float(input("Enter side of a square :"))
    a=s*s
    print("area of square :",a)
elif(z==2):
    l=float(input("Enter length of rectangle :"))
    b=float(input("Enter breadth of rectangle :"))
    a=l*b
    print("area of rectangle :",a)
elif(z==3):
    x=float(input("Enter first of triangle :"))
    y=float(input("Enter second side of triangle :"))
    m=float(input("Enter third side of triangle :"))
    s=(x+y+m)/2
    a=(s*(s-x)*(s-y)*(s-m))**0.5
    print("area of triangle :",a)
elif(z==4):
    r=float(input("Enter radius of circle :"))
    a=3.14*r*r
    print("area of circle :",a)
elif(z==5):
    l=float(input("Enter length of cuboid :"))
    b=float(input("Enter breadth of cuboid :"))
    h=float(input("Enter height of cuboid :"))
    a=2*(l*b+b*h+h*l)
    print("Total surface area of cuboid :",a)
elif(z==6):
    s=float(input("Enter side of cube :"))
    a=6*(s)**2
    print("Total surface area of cube :",a)
elif(z==7):
    r=float(input("Enter radius of cylinder :"))
    h=float(input("Enter height of cylinder"))
    a=2*3.14*h*(r+h)
    print("Total surface area of cylinder :",a)
elif(z==8):
    r=float(input("Enter radius of sphere :"))
    a=4*22/7*r*r
    print("Total surface area of sphere :",a)
elif(z==9):
    r=float(input("Enter radius of hemisphere :"))
    a=3*3.14*r*r
    print("Total surface area of hemisphere :",a)
elif(z==10):
    h=float(input("Enter height of frustum :"))
    r=float(input("Enter top radius of frustum :"))
    R = float(input("Enter bottom radius of frustum :"))
    l = (h*h+(r-R)**2)**0.5
    a = 3.14 * l * (r + R) + 3.14 * r * r + 3.14 * R * R
    print("Total surface area of frustum :", a)
else:
    print("                **********INVALID****INPUT**********")



