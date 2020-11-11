# EXERCÍCIOS
 #caculo aluguel de carro
 dias = int(input('Quantos dias alugado?'))
km = float(input('Quantos km rodados?? '))
pago = (dias * 60) + (km * 0.15)
print('O total é R$ {:.2f}.'.format(pago))
