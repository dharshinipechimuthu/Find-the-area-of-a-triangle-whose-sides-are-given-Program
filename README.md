# Find-the-area-of-a-triangle-whose-sides-are-given-Program
import math

a = float(input("Enter side a: "))
b = float(input("Enter side b: "))
c = float(input("Enter side c: "))

s = (a + b + c) / 2
area = math.sqrt(s * (s - a) * (s - b) * (s - c))

print("Area of the triangle is:", area)

Output:
Enter side a: 3
Enter side b: 4
Enter side c: 5
Area of the triangle is: 6.0
