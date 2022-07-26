# Find-the-average-of-N-numbers-in-python

This program is about how to find the average of given numbers by user in python.

Source Code:

num = int(input("How many numbers ? "))
total_sum = 0
for i in range(num):
    number = float(input("Enter any numbers "))
    total_sum += number
avg = total_sum / num
print("The average is ", avg)
