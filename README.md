# Q.29
# Get user input
n = int(input("Enter a number: "))

# Create the multiplication table using list comprehension
table = [(i*10) for i in range(1, n+1)]

# Print the table using lambda function
print(lambda table: '\n'.join(map(str, table)),(table))
