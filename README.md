# cls-obj
# printing even and odd numbers using class and object
class number:
    evens=[]
    odds=[]
    def __init__(self,num):
        self.num=num
        if num%2==0:
            number.evens.append(num)
        else:
            number.odds.append(num)
    print("even number",number.evens)
    print("odd number",number.odds)
num1=number(21)
num2=number(30)
num3=number(43)
num4=number(56)
num5=number(65)

# output
even number [30, 56]
odd number [21, 43, 65]
