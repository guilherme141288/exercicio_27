# exercicio_27

#speed check


speed = int (input ('qual a velocidade do carro?' ))

if speed <= 100:
    print ('Tenha um bom dia! Dirija com segurança')
else:
    multa = (speed -100) * 7
    print('Multado!, voce excedeu o limite de velocidade de 100km/h')
    print ('voce deve pagar uma multa de R${} ' .format (multa))
    print ('tenha um bom dia dirija com cuidado')
