# Distance-Calculator-1
#Calculator that calculates distance

import math
x1 = int(input("x1: "))

x2 = int(input("x2: "))

y1 = int(input("y1: "))

y2 = int(input("y2: "))

#This is the calculation part
dis = (x2-x1)
fin = (math.pow(2, dis))
nim = (y2-y1)
mon = (math.pow(2, nim))

print("The distance between the two points is: ", fin + mon ** 2)
#That concludes the program

#The output correctly shows the answer (I think)
