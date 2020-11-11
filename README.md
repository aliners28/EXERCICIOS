# EXERCÍCIOS
 primeiro repositorio de exercicios em python
#conversor de medidas
medida = float(input('Digite a medida em metros: '))
km = medida//1000
hm = medida//100
dam = medida//10
dm = medida*10
cm = medida*100
mm = medida*1000
print('Medida em metros: {}.'
      '\nMedida em kilômetro: {:.0f}.'
      '\nMedida em hectômetro: {:.0f}.'
      '\nMedida em decâmetro: {:.0f}.'
      '\nMedida em decímetros: {:.0f}'
      '\nMedida em centímetros: {:.0f}.'
      '\nMedida em milímetros: {:.0f}.'.format( medida,km, hm, dam, dm, cm, mm))
