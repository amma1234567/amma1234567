# Implement a recursie function to calculate the factorial of a given number

def fact_rec(n):
 if n==0 or n==1:
   return 1
 else:
   return n*fact_rec(n-1)

number=int(input("Enter a value:"))
res=fact_rec(number)

print("the factorial of {} is {}". format(number, res))

<!---
amma1234567/amma1234567 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
