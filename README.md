# lab-3
'''
# Find numbers which are divisible by 7 and multiple of 5 between a range 1500 and 2700


nl = []


for x in range(1500, 2701):

    if (x % 7 == 0) and (x % 5 == 0):
 
        nl.append(str(x))


print(','.join(nl))



# celcius to fahrenheit

celsius = int(input("Enter the Temperature in Celsius :\n"))
fahrenheit = (1.8 * celsius) + 32
print("Temperature in Fahrenheit :", fahrenheit)

fahrenheit = int(input("Enter a temperature in fahrenheit: \n"))
celsius = int((fahrenheit - 32) * 5/9)
print("temperature in celcious :" , celsius )


'''

# Import the 'random' module to generate random numbers
import random

# Generate a random number between 1 and 10 (inclusive) as the target number
target_num, guess_num = random.randint(1, 10), 0

# Start a loop that continues until the guessed number matches the target number
while target_num != guess_num:
    # Prompt the user to input a number between 1 and 10 and convert it to an integer
    guess_num = int(input('Guess a number between 1 and 10 until you get it right : '))

# Print a message indicating successful guessing once the correct number is guessed
print('Well guessed!') 
