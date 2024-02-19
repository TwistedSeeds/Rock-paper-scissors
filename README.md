#rock paper sissors
'paper' > 'rock'
'sissors' > 'paper'
'rock' > 'sissors'
import random
a=random.randint(1,3)
if a == 1:
    a = 'paper'
if a == 2:
    a = 'sissors'
if a == 3:
    a = 'rock'
Name = input('what is you name? ')
Answer = int(input('paper 1 sissors 2 rock 3 '))
if Answer == 1:
    Answer = 'paper'
if Answer == 2:
    Answer = 'sissors'
if Answer == 3:
    Answer = 'rock'
print(a + ' ' + 'and' ' ' + Answer)
if a > Answer:
    print('computer wins')
if Answer > a:
    print(Name + ' ' + 'wins')
