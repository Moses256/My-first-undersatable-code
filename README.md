# My-first-undersatable-code
# Just a bar entrence code 

name = input("Enter your name: ")
age = input("Hello " + name + " how old are you? ")
real_age = int(age)
never_come_back = False
soda = ['cola', 'fanta', 'sprite']

if real_age >= 20:
    print('You can ge in')
    drink = input('What would you like to drink? ')
    if drink == soda[0]:
        print('your ' + drink + ' is on the way')
    elif drink == soda[1]:
        print('your ' + drink + ' is on the way')
    elif drink == soda[2]:
        print('your ' + drink + ' is on the way')
    else:
        print("We do not have that drink here")

else:
    print('You cant get in')
    come_back = input('Will you ever come back here? ')
    if come_back == 'no':
        print('Okay stay in school')
    elif come_back == 'yes'.upper():
        print('Cool')
