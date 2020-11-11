# EXERCÍCIOS
from random import randint
from time import sleep

computador = randint(0,10)#faz o computador pensar
print( '-=-' * 10)
print('Vou pensar em um numero de 0 a 10, tente adivinhar...')
print( '-=-' * 10)
jogador = int(input('Em que numero eu pensei??'))#jogador tenta adivinhar
print('Processando ...')
sleep(3)
if jogador == computador:
    print('Parabéns vc me venceu!')
else:
    print('Ganhei! Eu pensei no numero {} e não no {}'.format(computador, jogador))

