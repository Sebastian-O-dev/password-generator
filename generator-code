lowercase_letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z']
uppercase_letters = ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

import random

print("""Welcome to the ProPassword Generator. You will be asked 4 questions regarding the password you would like to 
generate.
You will be asked to decide the number of lowercase letters, uppercase letters, symbols and numbers (in this order) to 
be used in generating your password.
Your password will be then generated using the program, and randomised in a way which meets top security standards for 
passwords.\n""")

nr_lowercase_letters = int(input("How many lowercase letters are to be used in your password?: "))
nr_uppercase_letters = int(input("How many uppercase letters are to be used in your password?: "))
nr_symbols = int(input("How many symbols are to be used in your password?: "))
nr_numbers = int(input("How many numbers are to be used in your password?: "))


password = []

for i in range(0, nr_lowercase_letters):
    password.append(random.choice(lowercase_letters))

for j in range(0, nr_uppercase_letters):
    password.append(random.choice(uppercase_letters))

for k in range(0, nr_symbols):
    password.append(random.choice(symbols))

for l in range(0, nr_numbers):
    password.append(random.choice(numbers))

# could print: print("Your not randomised password is " + "".join(password))

randomised_password = password[:]

random.shuffle(randomised_password)

print("Your randomised password is " + "".join(randomised_password))
