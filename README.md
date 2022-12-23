# Quiz-Game.py
This is a short program Just for learning purpose.
print("Welcome to my computer quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)")
score = 0

answer = input("What year was the very first model of the iPhone released? ")
if answer.lower() == "2007":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What’s the shortcut for the “copy” function on most computer? ")
if answer.lower() == "ctrl c":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is often seen as the smallest unit of memory?")
if answer.lower() == " kilobyte":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input(" Is Java a type of OS? ")
if answer.lower() == "No":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 4) * 100) + "%.")
