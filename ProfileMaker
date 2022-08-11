print('______________________________Dating Profile Maker______________________________')
print('Please input the date:')
day = int(input('Day: '))
month = input('Month (eg: \'january\', \'february\',...): ')
year = int(input('Year: '))
if month.lower() == 'january':
    month = 1
elif month.lower() == 'february':
    month = 2
elif month.lower() == 'march':
    month = 3
elif month.lower() == 'april':
    month = 4
elif month.lower() == 'may':
    month = 5
elif month.lower() == 'june':
    month = 6
elif month.lower() == 'july':
    month = 7
elif month.lower() == 'august':
    month = 8
elif month.lower() == 'september':
    month = 9
elif month.lower() == 'october':
    month = 10
elif month.lower() == 'november':
    month = 11
elif month.lower() == 'december':
    month = 12
if 4 < month:
    myage = year - 2003
elif 4 > month:
    myage = year - 2003 - 1
elif 4 == month:
    if 22 < day:
        myage = year - 2003
    elif 22 > day:
        myage = year - 2003 - 1
    elif 22 == day:
        myage = year - 2003
        print(f'Happy birthday to me!')
print(f'''My Profile (author):
My name is Alex Marques. I am demiboy.
Please call me by he/him. I like men.
I was born on 4/22/2003, therefor I am {myage} years old.
I like anime, TV series, horror movies, games, python, marcial arts, shopping, chocolate and animals.
I have a dog named Max.''')
run = 'y'
while run == 'y':
    firstname = input('Your first name: ')
    lastname = input('Your last name (or prefered middle name): ')
    nickname = input('What do I call you?: ')
    bday = int(input('The day you were born: '))
    bmonth = input('The month you were born (don\'t abreviate): ')
    if bmonth.lower() == 'january':
        bmonth = 1
    elif bmonth.lower() == 'february':
        bmonth = 2
    elif bmonth.lower() == 'march':
        bmonth = 3
    elif bmonth.lower() == 'april':
        bmonth = 4
    elif bmonth.lower() == 'may':
        bmonth = 5
    elif bmonth.lower() == 'june':
        bmonth = 6
    elif bmonth.lower() == 'july':
        bmonth = 7
    elif bmonth.lower() == 'august':
        bmonth = 8
    elif bmonth.lower() == 'september':
        bmonth = 9
    elif bmonth.lower() == 'october':
        bmonth = 10
    elif bmonth.lower() == 'november':
        bmonth = 11
    elif bmonth.lower() == 'december':
        bmonth = 12
    byear = int(input('The year you were born: '))
    if bmonth < month:
        age = year - byear
    elif bmonth > month:
        age = year - byear - 1
    elif bmonth == month:
        if bday < day:
            age = year - byear
        elif bday > day:
            age = year - byear - 1
        elif bday == day:
            age = year - byear
            print(f'Happy birthday!')
    gender = input('Your gender: ')
    pronouns = input("Your prefered pronouns ('he/him', 'she/her' or 'they/them'): ")
    orientation = input('Your sexual orientation (\'heterossexual\', \'homossexual\', \'bissexual\' or \'none of these\'): ')
    if orientation == 'heterossexual':
        if pronouns == 'he/him':
            orientation =='I like women.'
        elif pronouns == 'she/her':
            orientation = 'I like men.'
    elif orientation == 'homossexual':
        if pronouns == 'he/him':
            orientation = 'I like men.'
        elif pronouns == 'she/her':
            orientation = 'I like women.'
    elif orientation == 'bissexual':
        orientation == 'I like both men and women.'
    elif orientation == 'none of these':
        orientation = input('Please specify (Eg:\'I like men\', \'I like women\', \'I like men and women\', \'I don\'t fall for gender\',...): ')
    interests = input('What are your interests?: ')
    note = input('Anything else you want to add? (\'y\' or \'n\')')
    if note == 'y':
        note = input('What? (The first letter is in CAPS LOCK (or shift). Don\'t forget to add a period at the end): ')
        if firstname == nickname:
            print(f'''Your profile:
My name is {firstname} {lastname}. I am {gender}.
Please call me by {pronouns}. {orientation}
I was born on {bmonth}/{bday}/{byear}, therefor I am {age} years old.
I like {interests}.
{note}''')
        elif lastname == nickname:
            print(f'''Your profile:
My name is {firstname} {lastname}. I am {gender}.
Please call me by {pronouns}. {orientation}
I was born on {bmonth}/{bday}/{byear}, therefor I am {age} years old.
I like {interests}.
{note}''')
        else:
            print(f'''Your profile:
My name is {firstname} {lastname}. But you can call me {nickname}.
I am {gender}. Please call me by {pronouns}. {orientation}
I was born on {bmonth}/{bday}/{byear}, therefor I am {age} years old.
I like {interests}.
{note}''')
    elif note == 'n':
        if firstname == nickname:
            print(f'''Your profile:
My name is {firstname} {lastname}. I am {gender}.
Please call me by {pronouns}. {orientation}
I was born on {bmonth}/{bday}/{byear}, therefor I am {age} years old.
I like {interests}.''')
        elif lastname == nickname:
            print(f'''Your profile:
My name is {firstname} {lastname}. I am {gender}.
Please call me by {pronouns}. {orientation}
I was born on {bmonth}/{bday}/{byear}, therefor I am {age} years old.
I like {interests}.''')
        else:
            print(f'''Your profile:
My name is {firstname} {lastname}. But you can call me {nickname}.
I am {gender}. Please call me by {pronouns}. {orientation}
I was born on {bmonth}/{bday}/{byear}, therefor I am {age} years old.
I like {interests}.''')
    run = input('Do you want to try again? (\'y\' or \'n\'): ')
