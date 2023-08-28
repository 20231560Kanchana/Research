# Research
Assessment 3: Research Repository
Assessment 3: Research Repository
# DRY principle helps to save time while avoiding to have creat same code repedatedly for a same result.
class Circle:
    def __init__(self, radius):
        self.radius = radius
    
    def area(self):
        return 3.14159 * self.radius ** 2

class Area:
    def run(self):
        circle = Circle(5)
        circle_area = Circle.area(circle)
        print(circle_area)

area= Area()
area.run()
# below is a example of not using DRY pricple, if you want area of 20 circles you can use DRY princple and get the result at once intead having to write 20 lines. 
circle1= 3.14159 * 3 ** 2
print(circle1)
circle2= 3.14159 * 5 ** 2
print(circle2)
