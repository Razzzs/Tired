# Tired

yes = 'go sleep'
no = 'if not tired'

question = input('Are you tired? ')

if question.lower() == 'yes':
    answer = input('Why? ')
    print(f'You said you are tired. {yes}')
elif question.lower() == 'no':
    answer = input('Why not? ')
    print(f'You said you are not tired. {no}')
else:
    print('Invalid response. Please enter "yes" or "no".')
