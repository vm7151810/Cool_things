#To calulate pi when the number of points that lie on a 0-1 2D plane
import random
  n=int(input("No.of points: "))#more the the number of points, more accurate the value of pie will. Take atleast 1000 for good results
  a=0#total number of points inside the circle
  b=0#total number of points
  for i in range(n):
    x=random.uniform(0,1)#chooses a random x-coordinate randomly between 0 and 1 on the coordinate system
    y=random.uniform(0,1)#chooses a random y-coordinate randomly between 0 and 1 on the coordinate system
    z=(x**2 + y**2)**(1/2)# distance of the point from origin
    if z<=1:
      a+=1#if it lies in the circle
    b+=1#always add no matter in or out the cirlce
  print(4*(a/b))
'''the ratio of the area of cirlce upon area of square(side length = diameter of the circle)must be equal to the ratio of number of points in the circle upon total points points in the square
area of cirlce/area of square = pi/4. Taking 4 to the other gives us the formula in the print statement'''

    
        

