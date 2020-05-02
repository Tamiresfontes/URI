# Fórmula de Bhaskara

Leia 3 valores de ponto flutuante e efetue o cálculo das raízes da equação de Bhaskara. Se não for possível calcular as raízes, mostre a mensagem correspondente “Impossivel calcular”, caso haja uma divisão por 0 ou raiz de numero negativo.

## Entrada

Leia três valores de ponto flutuante (double) A, B e C.

## Saída

Se não houver possibilidade de calcular as raízes, apresente a mensagem "Impossivel calcular". Caso contrário, imprima o resultado das raízes com 5 dígitos após o ponto, com uma mensagem correspondente conforme exemplo abaixo. Imprima sempre o final de linha após cada mensagem.

## Resposta

x = input().split()

A, B, C = x

A = float(A)

B = float(B)

C = float(C)

if B**2 - 4*A*C < 0 or A == 0.0:

    print("Impossivel calcular")

else: 

    x1 = (-B + (B**2 - 4*A*C) **(1/2)) / (2*A) 

    x2 = (-B - (B**2 - 4*A*C) **(1/2)) / (2*A) 

    print("R1 = {:.5F}".format(x1))

    print("R2 = {:.5F}".format(x2))