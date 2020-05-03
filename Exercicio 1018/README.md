# Cédulas

Leia um valor inteiro. A seguir, calcule o menor número de notas possíveis (cédulas) no qual o valor pode ser decomposto. As notas consideradas são de 100, 50, 20, 10, 5, 2 e 1. A seguir mostre o valor lido e a relação de notas necessárias.

## Entrada

O arquivo de entrada contém um valor inteiro N (0 < N < 1000000).

## Saída

Imprima o valor lido e, em seguida, a quantidade mínima de notas de cada tipo necessárias, conforme o exemplo fornecido. Não esqueça de imprimir o fim de linha após cada linha, caso contrário seu programa apresentará a mensagem: *“Presentation Error”*.


|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|576                                        |576                                      |
|                                           |5 nota(s) de R$ 100,00                   |
|                                           |1 nota(s) de R$ 50,00                    |
|                                           |1 nota(s) de R$ 20,00                    |
|                                           |0 nota(s) de R$ 10,00                    |
|                                           |1 nota(s) de R$ 5,00                     |
|                                           |0 nota(s) de R$ 2,00                     |
|                                           |1 nota(s) de R$ 1,00                     |
|11257                                      |11257                                    |
|                                           |112 nota(s) de R$ 100,00                 |
|                                           |1 nota(s) de R$ 50,00                    |
|                                           |0 nota(s) de R$ 20,00                    |
|                                           |0 nota(s) de R$ 10,00                    |
|                                           |1 nota(s) de R$ 5,00                     |
|                                           |1 nota(s) de R$ 2,00                     |
|                                           |1 nota(s) de R$ 1,00                     |
|503                                        |503                                      |
|                                           |5 nota(s) de R$ 100,00                   |
|                                           |0 nota(s) de R$ 50,00                    |
|                                           |0 nota(s) de R$ 20,00                    |
|                                           |0 nota(s) de R$ 10,00                    |
|                                           |0 nota(s) de R$ 5,00                     |
|                                           |1 nota(s) de R$ 2,00                     |
|                                           |1 nota(s) de R$ 1,00                     |



## Resposta

N = int(input())

print(N)

CED100 = N // 100

N = N - CED100*100

CED50 = N // 50

N = N - CED50*50

CED20 = N // 20

N = N - CED20*20

CED10 = N // 10

N = N - CED10*10

CED5 = N // 5

N = N - CED5*5

CED2 = N // 2

N= N - CED2 * 2

CED1 = N // 1

print("{:.0F} nota(s) de R$ 100,00". format (CED100))

print("{:.0F} nota(s) de R$ 50,00". format (CED50))

print("{:.0F} nota(s) de R$ 20,00". format (CED20))

print("{:.0F} nota(s) de R$ 10,00". format (CED10))

print("{:.0F} nota(s) de R$ 5,00". format (CED5))

print("{:.0F} nota(s) de R$ 2,00". format (CED2))

print("{:.0F} nota(s) de R$ 1,00". format (CED1))