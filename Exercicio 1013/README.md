# O maior

Faça um programa que leia três valores e apresente o maior dos três valores lidos seguido da mensagem “eh o maior”. Utilize a fórmula:

*Maior AB = ( a + b + abs (a - b)) / 2*

Obs.: a fórmula apenas calcula o maior entre os dois primeiros (a e b). Um segundo passo, portanto é necessário para chegar no resultado esperado.

## Entrada

O arquivo de entrada contém três valores inteiros.

## Saída

Imprima o maior dos três valores seguido por um espaço e a mensagem "eh o maior".

## Resposta

V= input().split()

a = int (V[0])

b = int (V[1])

c = int (V[2])

MaiorAB= (a + b + abs (a - b)) / 2

if MaiorAB < c:

      print(c,"eh o maior")

elif MaiorAB > c:

      print("{:.0F}".format(MaiorAB),"eh o maior")