import random
running = True
tries = 0
r = random.randint(1,100)
name = input('Your name: ')
while running:
    guess = int(input('Enter a guess between 1 and 100: '))
    if guess < r:
        print('Too low.')
        tries += 1
        print(f'{tries} tries so far.')
    elif guess > r:
        print('Too high.')
        tries += 1
        print(f'{tries} tries so far.')
    elif int(guess) == r:
        tries += 1
        print(f'Congratulations {name}, you guessed it in {tries} tries!')
        x = input("Do you want to play again? ('y' or 'n')")
        if x == 'y':
            tries = 0
            r = random.randint(1,100)
            running = True
        elif x == 'n':
            print(f"Goodbye {name}.")
            break
