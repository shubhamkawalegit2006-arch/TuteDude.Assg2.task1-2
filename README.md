#Check if a number is Even or Odd
Number=int(input("Enter a number:"))
if Number%2!=0:
    print(f"{Number} is an odd number")
else:
    print(f"{Number} is an even number")


#Sum of Integers from 1 to 50 using a loop
for i in range(1,51):
    print(i)
sum=i*(i+1)/2
print("The sum of numbers from 1 to 50:",sum)
