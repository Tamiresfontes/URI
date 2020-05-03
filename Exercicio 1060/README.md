# Números positivos

Faça um programa que leia 6 valores. Estes valores serão somente negativos ou positivos (desconsidere os valores nulos). A seguir, mostre a quantidade de valores positivos digitados.

## Entrada

Seis valores, negativos e/ou positivos.

## Saída

Imprima uma mensagem dizendo quantos valores positivos foram lidos.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|-7                                         |4 valores positivos                      |
|-5                                         |                                         |
|6                                          |                                         |
|-3.4                                       |                                         |
|4.6                                        |                                         |
|12                                         |                                         |

## Resultado

t = 0 
for x in range(1,7):
        valor = float(input())
        if valor > 0:
             t = t + 1
print("{} valores positivos".format(t))