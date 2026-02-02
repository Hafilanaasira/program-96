# program-96
# Initialize
c = 0
product = 1.0

# Input number of values
count = int(input("Enter the number of values: "))

# Input numbers and calculate product
while c < count:
    x = float(input("Enter a real number: "))
    product *= x
    c += 1

# Calculate geometric mean
gm = pow(product, 1.0 / count)

# Print result
print("The geometric mean is:", gm)
output
Enter the number of values: 4
Enter a real number: 2
Enter a real number: 8
Enter a real number: 4
Enter a real number: 16
The geometric mean is: 5.656854249492381
