
n=int(input("Enter the number "))
sum1=0
m=n
while n>0:
    x=n%10
    sum1=(sum1*10)+x
    n=n//10
    
if sum1 == m:
    print("palindrom")
else:
    print("not palindrom")
