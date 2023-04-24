# Python-coding
Write a program to reverse an integer in Python?
num = int(input("Enetr number:"))
rev = 0
while num > 0:
    d = num%10
    rev = rev*10 + d
    print(rev)
    num = num//10
print("Reverse number:", rev)


Write a program in Python to check given number is prime or not?
num = int(input("Enetr number:"))
flag = False

for i in range(2,num):
    if num % i ==0:
        flag = True
        break
if flag:
    print("Number is not prime")
else:
    print("Number is prime")
		
		
