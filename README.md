# RK22MQA35
num=int(input("Enter the number you want to check\n"))
temp=1
k=0
a=0
summ=0
while summ<=num:
    summ=temp+k
    temp=summ
    k=temp
    if summ==num:
        a=a+1
        print("Yes. {} is a fibonnaci number".format(num))
        break
if a==0:
    print("No. {} is NOT a fibonacci number".format(num))
