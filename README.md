from ast import Delete
from random import randrange
print("Добро пожалывать в рулетку!\n")
print('''Крутите барабан! Нажмите 1, 2, 3, 4 или 5\n''')
o = int(input())
if o == 1:
    print('барабан остановился...')
elif o == 2:
    print('"Умру ли я сейчас? " - думаеете вы...')
elif o == 3:
        print('"Я готов..." - думаеете вы...')
elif o == 4:
        print('"БЫСТРЕЕЕЕЕЕ! - сказал судья...')
elif o == 5:
        print('"Госпада поторопитесь!!!" - сказал судья...')
else:
        print('"Я не выживу" - подумали вы...')
print('3')
print('2')
print('1')
print('Огонь')
comp = randrange(5)
if comp == 1 or comp == 0 or comp == 2 or comp == 3:
    print('Вы убиты...')
elif comp == 4:
    print(' Вы выжили...' )
