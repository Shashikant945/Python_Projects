# FizzBuzz Program

# Input: Prompt the user to enter the range limit
num = int(input("Enter the number till you want the list: "))

# Initialize an empty list to store the results
fizzbuzz_list = []

# Loop through numbers from 1 to the specified number
for i in range(1, num + 1):
    # Check if the number is divisible by both 3 and 5
    if i % 3 == 0 and i % 5 == 0:
        fizzbuzz_list.append("FizzBuzz")
    # Check if the number is divisible by 3
    elif i % 3 == 0:
        fizzbuzz_list.append("Fizz")
    # Check if the number is divisible by 5
    elif i % 5 == 0:
        fizzbuzz_list.append("Buzz")
    # If the number is not divisible by 3 or 5, append the number itself
    else:
        fizzbuzz_list.append(i)

# Output: Print the final list
print(fizzbuzz_list)
