# escoladofuturo
import random
#número de pessoas a serem sorteadas
#de acordo com o número inicial e final
npsorteadas=int(input("digite o número de  pessoas a serem sorteada: "))
n1=int(input("digite o número inicial: "))
n2=int(input("digite o número final: "))

lista_random=[random.randint(n1,n2)]
print(lista_random)

import random
lista_random=[random.randint(n1,n2) for n in range(npsorteadas)]
#imprime a lista com os 10 números que foram sorteadas
print(lista_random)
#imprime o número mínimo
print(min(lista_random))
#imprime o número máximo
print(max(lista_random))
