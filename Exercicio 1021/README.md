# Notas e moedas

Leia um valor de ponto flutuante com duas casas decimais. Este valor representa um valor monetário. A seguir, calcule o menor número de notas e moedas possíveis no qual o valor pode ser decomposto. As notas consideradas são de 100, 50, 20, 10, 5, 2. As moedas possíveis são de 1, 0.50, 0.25, 0.10, 0.05 e 0.01. A seguir mostre a relação de notas necessárias.

## Entrada

O arquivo de entrada contém um valor de ponto flutuante N (0 ≤ N ≤ 1000000.00).

## Saída

Imprima a quantidade mínima de notas e moedas necessárias para trocar o valor inicial, conforme exemplo fornecido.

Obs: Utilize ponto (.) para separar a parte decimal.

## Resposta

entrada = float(input())

resto = entrada

notas100 = int(entrada / 100)

resto = resto%100

notas50 = int(resto/50)

resto = resto%50

notas20 = int(resto/20)

resto = resto%20

notas10 = int(resto/10)

resto = resto%10

notas5 = int(resto/5)

resto = resto%5

notas2 = int(resto/2)

resto = resto%2

resto = resto * 100

moedas1 = int(resto/100)

resto = resto%100

moedas50 = int(resto/50)

resto = resto%50

moedas25 = int(resto/25)

resto = resto%25

moedas10 = int(resto/10)

resto = resto%10

moedas5 = int(resto/5)

resto = resto%5

moedas01 = int(resto/1)

print("NOTAS:\n{} nota(s) de R$ 100.00\n{} nota(s) de R$ 50.00\n{} nota(s) de R$ 20.00\n{} nota(s) de R$ 10.00\n{} nota(s) de R$ 5.00\n{} nota(s) de R$ 2.00\nMOEDAS:\n{} moeda(s) de R$ 1.00\n{} moeda(s) de R$ 0.50\n{} moeda(s) de R$ 0.25\n{} moeda(s) de R$ 0.10\n{} moeda(s) de R$ 0.05\n{} moeda(s) de R$ 0.01".format(notas100,notas50,notas20,notas10,notas5,notas2,moedas1,moedas50,moedas25,moedas10,moedas5,moedas01))