# revisaopython

## calculo de consumo


distancia = float(input(f'Digite a distancia em Km: '))
combustivel_gasto = float(input(f'Digite o total de combustível gasto em litros: '))
consumo_medio = distancia / combustivel_gasto 

print(f' O consumo médio é: {consumo_medio}.')

if consumo_medio <= 8:
    print('Consumo elevado! 🚗📉')
elif consumo_medio <= 12:
    print('Consumo médio 🚗📊')
else:
    print('Consumo econômico! 🚗📈')

print(f' O consumo médio é: {consumo_medio}.')

## calculo de pontuacao IA

nome_ia = input('Digite o nome da IA')
pontuacao_ia = float(input('Digite a pontuacao'))

if pontuacao_ia >= 39.9:
    print(f' Com esta pontuação{nome_ia} se encaixa em IA Aprendiz!⚙️')
elif pontuacao_ia >= 40:
    print(f' Com esta pontuação{nome_ia} se encaixa em "IA Mediana! ⚠️ ')
elif pontuacao_ia >= 69.9:
    print(f' Com esta pontuação{nome_ia} se encaixa em IA Boa! 📈')
elif pontuacao_ia >= 90: 
    print(f'Com esta pontuacao{nome_ia} se encaixa em IA Avançada! ✨🏆')
elif pontuacao_ia >= 100:
    print(f'Com esta pontuação{nome_ia} ... ❌é invalida❌!!')
else:
    print(F'Com esta pontuação... Evite{nome_ia}!! 📉')



