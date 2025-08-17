# TASK-1-AND-TASK-2-Number-is-Even-or-Odd-AND-Sum-of-Integers-from-1-to-50-Using-a-Loop

Task 1: Check if a Number is Even or Odd

num = int(input("Enter a number: "))
if(num%2==0):
    print("Even")
else:
    print("Odd")

Task 2: Sum of Integers from 1 to 50 Using a Loop

total = 0
for i in range(1, 51):
    print(i)
    total += i
print(total)
