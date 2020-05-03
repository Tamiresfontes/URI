# Números pares

Faça um programa que mostre os números pares entre 1 e 100, inclusive.

## Entrada

Neste problema extremamente simples de repetição não há entrada.

## Saída

Imprima todos os números pares entre 1 e 100, inclusive se for o caso, um em cada linha.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|                                           |2                                        |
|                                           |4                                        |
|                                           |6                                        |
|                                           |...                                      |
|                                           |100                                      |

## Resposta

for t in range(1,101):

        if t % 2 == 0:

                print(t)