def calculator():
    while 1:
        operation = input(
        '''
        Please type in the math operation you would like to complete:
        + for addition
        - for subtraction
        * for multiplication
        / for division
        '''
        )
        if operation in ('+','-','*','/'):
            break

        else:
            print('Wrong type')

            
    number_1 = float(input('Enter your first number:'))
    number_2 = float(input('Enter your second number:'))

    # Addition
    if operation == '+':
        print('{} + {} ='.format(number_1,number_2))
        print('%.8f'%(number_1 + number_2))


    # Subtraction
    elif operation == '-':
        print('{} - {} ='.format(number_1,number_2))
        print('%.8f'%(number_1 - number_2))



    # Multiplication
    elif operation == '*':
        print('{} * {} ='.format(number_1,number_2))
        print('%.8f'%(number_1 * number_2))



    # Division
    elif operation == '/':
        print('{} / {} ='.format(number_1,number_2))
        print('%.8f'%(number_1 / number_2))



    else:
        print('You have not typed a valid operator, please run the program again.')




    again()



def again():
    calc_again = input('''
Do you want to calculate again?
Please type Y for YES or N for NO.
''' )
    if calc_again.upper() == 'Y':
        calculator()
        
    elif calc_again.upper() == 'N':
        print('See you later.')
        
    else:
        again()

calculator()
