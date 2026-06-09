# programs-on-numeric-data
#programs like prime, happy,buzz,armstrong,strong
# armstrong number

num=int(input("enter any nnumber"))
sum=0
temp=num
while(temp>0):
 rem=temp%10
 sum=sum+rem**3
 temp=temp//10

if sum==num:
   print("armstrong number")
else:
  print("not armsrong number ")

    #A Buzz Number is a number that:
    #Ends with 7, or
    #Is divisible by 7
num = int(input("Enter a number: "))
if num % 10 == 7 or num % 7 == 0:
    print("Buzz Number")
else:
    print("Not a Buzz Number")


num=int(input("enter any number"))
print("factor are :")
for i in range(1,num+1):
    if num%i == 0:
        print(i)

    # reverse of number and pallindrome
num=int(input("enter any number"))
rev=0
original=num
while(num>0):
  num1=num%10
  rev=rev*10+num1
  num=num//10
print(rev)  

if original==rev:
  print("number is pallindrome")
else:
  print("number is not pallindrome")

    #perfect number
#A Perfect Number is a number that is equal to the sum of its proper divisors (excluding the number itself).
num = int(input("Enter a number: "))
sum = 0
for i in range(1, num):
    if num % i == 0:
        sum = sum + i
if sum == num:
    print("Perfect Number")
else:
    print("Not a Perfect Number")
    
num=int(input("enter any number"))
if num<=1:
 print("not prime")
else:
  for i in range(2,num):
    if num % i==0:
      print("not prime")
      break 
  else:
     print("prime")

