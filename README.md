# Aula01
Aula1 exercícios
"""prova1=float(input("resultado nota 1: "))
prova2=float(input("resultado nota2:"))
soma=prova1+prova2
media=soma/2
print(" a media é",media)"""

"""peso=float(input("informe seu peso: "))
altura=float(input("informe sua altura: "))
imc=peso/(altura*2)
print(f"o resultado é {imc:.2f}")"""

"""tf=float(input("graus f: "))
tc=((tf-32)/9)*5
print(f"resultado temperatura é {tc:.2f}°C") transformação de temperatura"""

"""base=float(input("informe a base do triangulo: "))
altura=float(input("informe a altura do triangulo: "))
area=(base*altura)
print(f"a area do trianghulo é {area:.2f}")"""

brancos=int(input("informe a quantidade de votos brancos: "))
nulos=int(input("informe a quantidade de votos nulos"))
validos=int(input("informe a quantidade de votos validos"))
soma=brancos+nulos+validos
print(f"o total de votos do município é: {soma}")
print(f"percentual de votos brancos: {(brancos/soma)*100:.2f}%")
print(f"percentual de votos nulos: {(nulos/soma)*100:.2f}%")
print(f"percentual de votos validos: {(validos/soma)*100:.2f}%")
