# Pares entre cinco números

Faça um programa que leia 5 valores inteiros. Conte quantos destes valores digitados são pares e mostre esta informação.

## Entrada

O arquivo de entrada contém 5 valores inteiros quaisquer.

## Saída

Imprima a mensagem conforme o exemplo fornecido, indicando a quantidade de valores pares lidos.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|-7                                         |3 valores pares                          |
|-5                                         |                                         |
|6                                          |                                         |
|-4                                         |                                         |
|-12                                        |                                         |

## Resultados

valorpar = 0
for n in range(1,6):
    valor= int(input())
    if (valor % 2  == 0):
            valorpar = valorpar + 1
print("{} valores pares".format(valorpar))