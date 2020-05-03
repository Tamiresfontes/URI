# Positivos e Média

Leia 6 valores. Em seguida, mostre quantos destes valores digitados foram positivos. Na próxima linha, deve-se mostrar a média de todos os valores positivos digitados, com um dígito após o ponto decimal.

## Entrada

A entrada contém 6 números que podem ser valores inteiros ou de ponto flutuante. Pelo menos um destes números será positivo.

## Saída

O primeiro valor de saída é a quantidade de valores positivos. A próxima linha deve mostrar a média dos valores positivos digitados.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|-7                                         |4 valores positivos                      |
|-5                                         |7.4                                      |
|6                                          |                                         |
|-3.4                                       |                                         |
|4.6                                        |                                         |
|12                                         |                                         |

## Resposta

t = 0 
media = 0
for x in range(1,7):
        valor = float(input())
        if valor > 0:
            t = t + 1
            media = media + valor
print('{} valores positivos'.format(t))
print('{:.1f}'.format(media/t)) 