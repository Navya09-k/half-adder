a = int(input("Enter first bit (0 or 1): "))
b = int(input("Enter second bit (0 or 1): "))
sum_bit = a ^ b
carry = a & b
print("Sum =", sum_bit)
print("Carry =", carry)
