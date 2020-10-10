# class-learn
# in this we are learning basic programs with class , for understand class easily 

#calling class
class Circle():
    pi = 3.14                 #pi constant, so given as global variable

    def __init__(self,r):     # constructor of class
        self.r = r

    def getArea(self):        #for area
        area = Circle.pi*self.r*self.r
        print("circle area is :",area)

    def getCircumference(self):     #for circumference
        c = 2*Circle.pi*self.r
        print(" the circumference of circle is:", c)
        
# calling the functions
a = Circle(6) 
a.getArea()
a.getCircumference()
        
