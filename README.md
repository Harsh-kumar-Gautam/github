# github
learning

secret_number = 7
a = 0
i = 3
print("🎮 Welcome to the Number Guessing Game!")
print("I have selected a number between 1 and 10.")

while a < i:
    g = int(input("Enter your Guess: "))
    a += 1
    if g == secret_number:
        print("you won:")
        break
else:
    print("you failed")
