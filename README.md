# Exercicio042.py


r1 = float(input('Primeiro segmento: '))
r2 = float(input('Segundo segmento: '))
r3 = float(input('Terceiro segmento: '))
if r1 < r2  + r3 and r2 < r1 +r3 and r3 < r1 + r2:
    print('Os segmentos podem formar um trilangulo', end='')
    if r1 == r2 == r3:
        print(' Equilatero! ')
    if r1 != r2 != r3 != r1:
        print(' Escaleno! ')
    else:
        print(' Isosceles! ')
else:
    print('Os segmentos não podem formar um triangulo.')
    
