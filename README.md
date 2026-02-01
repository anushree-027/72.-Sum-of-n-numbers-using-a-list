# 72.-Sum-of-n-numbers-using-a-list
numbers = []
num = int(input("How many numbers: "))

for _ in range(num):
    x = int(input("Enter number: "))
    numbers.append(x)

print("Sum of numbers in the given list is:", sum(numbers))
