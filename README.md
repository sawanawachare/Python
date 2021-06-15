"""
@goal    : To calculate distance between two points

@author  : Swan
 
@versin  : 0.1

@date    : 2021-03-06

"""

x1=float(input("Please enter x cordinate of point 1 :"))
y1=float(input("Please enter y cordinate of point 1 :"))

x2=float(input("Please enter x cordinate of point 2 :"))
y2=float(input("Please enter y cordinate of point 2 :"))

x3=float(input("Please enter x cordinate of point 3 :"))
y3=float(input("Please enter y cordinate of point 3 :"))

# to calculate the distance between two points

d12=(((x1-x2)**2)+((y1-y2)**2))**0.5
d13=(((x1-x3)**2)+((y1-y3)**2))**0.5
d23=(((x2-x3)**2)+((y2-y3)**2))**0.5

print("Distance between point 1 with coordinates:",x1,y1,"and point 2 with coordinate",x2,y2,"is:",d12)
print("Distance between point 1 with coordinates:",x1,y1,"and point 3 with coordinate",x3,y3,"is:",d13)
print("Distance between point 2 with coordinates:",x2,y2,"and point 3 with coordinate",x3,y3,"is:",d23)
