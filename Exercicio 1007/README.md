# Diferença

Leia quatro valores inteiros A, B, C e D. A seguir, calcule e mostre a diferença do produto de A e B pelo produto de C e D segundo a fórmula: DIFERENCA = (A * B - C * D).

## Entrada

O arquivo de entrada contém 4 valores inteiros.

## Saída

Imprima a mensagem DIFERENCA com todas as letras maiúsculas, conforme exemplo abaixo, com um espaço em branco antes e depois da igualdade.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|5                                                                                    |
|6                                          |DIFERENÇA = -26                          |
|7                                                                                    |
|8                                                                                    |
|0                                                                                    |
|0                                          |DIFERENÇA = -56                          |
|7                                                                                    |
|8                                                                                    |
|5                                                                                    |
|6                                          |DIFERENÇA = 86                           |
|-                                                                                    |
|8                                                                                    |

## Resposta

A=int(input())

B=int(input())

C=int(input())

D=int(input())

DIFERENCA =(A * B - C * D)
print("DIFERENCA =",DIFERENCA)