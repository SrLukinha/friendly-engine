# friendly-engine
mini game bem simples de python, usando a biblioteca random
from random import choice
print('Vou pensar em um numero entre 0 e 5.')
nump=int(input('Em que numero pensei: '))
lista=[0,1,2,3,4,5]
random=choice(lista)
if random==nump:
    print('Parabens voce ganhou o jogo!!!')
else:
    print('Tente mais uma vez!!!')
