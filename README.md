class Student:
    def __init__(self,m1,m2,m3):
        self.m1=m1
        self.m2=m2
        self.m3=m3
    def average(self):
        return (self.m1+self.m2+self.m3)/3

a=int(input())
b=int(input())
c=int(input())
s=Student(a,b,c)
print("Average:",s.average())
Output
40
50
60
Average: 50.0
