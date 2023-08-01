# Paisesecapitais
Programa em Python utilizando dicionários para identificar a capital do país.

paisecap = {'Brasil':'Brasília','Portugal':'Lisboa','Argentina':'Buenos Aires','Japão':'Tóquio','Espanha':'Madrid'}

pais = input('Digite um país: ')

if pais in paisecap :
   print(f'A capital do {pais} é {(paisecap[pais])}')
else:
  print('Desculpe,não temos informações sobre a capital deste país!')
