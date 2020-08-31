# Python-Program-for-n-Fibonacci-number.py
a = 0
b = 1
n=int(input())
if n <= 0:
   print("Please enter a positive integer")
elif n == 1:
    print(a)
   
else:
    print(a)
    print(b)
    for i in range(2,n):
        
        
        c = a + b 
        a = b 
        b = c
        
        print(c)
