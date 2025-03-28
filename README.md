# Experiment-2

name = input("Enter your name:")
age = int(input("Enter your age:"))
if age >= 18:
     print("Congratulations",name,"you are elgible to vote!")




num = int(input("Enter a number:"))
if num%2 == 0:
    print(num,"is even")
else:
    print(num,"is odd")




num = int(input("Enter a number:"))
if num == 0:
    print("Zero")
elif num == 1:
    print("One")
elif num == 2:
    print("Two")
elif num == 3:
    print("Three")
elif num == 4:
    print("Four")
elif num == 5:
     print("Five")
elif num == 6:
     print("Six")
elif num == 7:
     print("Seven")
elif num == 8:
    print("Eight")
elif num == 9:
    print("Nine")
else:
    print("Number out of range")




num = int(input("Enter a number:"))
if num >= 1 and num <= 100:
    print("The number",num,"in between numbers")






N = int(input("Enter a number:"))
count = 0
num = 5
while count < N:
    print(num)
    num += 5
    count += 1





mylist = input("Enter a list of numbers seperated by space:")
mylist = list(map(int,mylist.split
sum = 0
for num in mylist:
    sum += num
print("The sum of numbers is:", sum)




num = 0
while num<=20:
    if num % 2 == 0:
        print(num,end=',')
    num += 1





for i in range(1,11):
    if i == 5:
        continue
    if i == 8:
        break
    print(i)

