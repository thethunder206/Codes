#Import libaries
import random

#Setting up random number and greeting user
print("Hello User! This is a number Guessing Game.")
number_1 = int(input("Please enter the first number of the range(2 Digit Number): "))
number_2 = int(input("Please enter the second number of the range(2 Digit Number): "))
random_number = random.randint(number_1, number_2)
print("The program selected it's number!")
attempts = int(input("How many attempts do you want to guess the number: "))

for i in range(attempts):
    #User Guessing first digit, wrong or right...
    random_number_new = str(random_number)
    firstinput = int(input("Enter Guess: "))
    firstinput_new = str(firstinput)
    if random_number_new == firstinput_new:
        print('Correct Number!')
        break
    elif random_number_new[0] == firstinput_new[0]:
        print('\nThe first digit is correct!')
    #User Guessing Second digit, wrong or right...
    elif random_number_new[1] == firstinput_new[1]:
        print('The Second digit is correct!')
    else:
        print('\nThe number is wrong!')
print(random_number)
print('Thanks for Playing!')
