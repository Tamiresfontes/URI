# Cálculo Simples

Neste problema, deve-se ler o código de uma peça 1, o número de peças 1, o valor unitário de cada peça 1, o código de uma peça 2, o número de peças 2 e o valor unitário de cada peça 2. Após, calcule e mostre o valor a ser pago.

## Entrada

O arquivo de entrada contém duas linhas de dados. Em cada linha haverá 3 valores, respectivamente dois inteiros e um valor com 2 casas decimais.

## Saída

A saída deverá ser uma mensagem conforme o exemplo fornecido abaixo, lembrando de deixar um espaço após os dois pontos e um espaço após o "R$". O valor deverá ser apresentado com 2 casas após o ponto.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|12 1 5.30                                  |VALOR A PAGAR: R$ 15.50                  |
|16 2 5.10                                  |                                         |
|13 2 15.30                                 |VALOR A PAGAR: R$ 51.40                  |
|161 4 5.20                                 |                                         |
|1 1 15.10                                  |VALOR A PAGAR: R$ 30.20                  |
|2 1 15.10                                  |                                         |

## Resposta

p1=input().split()

p2=input().split()

valor = (float(p1[1]) * float(p1[2])) + (float(p2[1] )* float(p2[2]))

print("VALOR A PAGAR: R$ {:.2F}". format(valor))