# Área 

Escreva um programa que leia três valores com ponto flutuante de dupla precisão: A, B e C. Em seguida, calcule e mostre:
a) a área do triângulo retângulo que tem A por base e C por altura.
b) a área do círculo de raio C. (pi = 3.14159)
c) a área do trapézio que tem A e B por bases e C por altura.
d) a área do quadrado que tem lado B.
e) a área do retângulo que tem lados A e B.

## Entrada

O arquivo de entrada contém três valores com um dígito após o ponto decimal.

## Saída

O arquivo de saída deverá conter 5 linhas de dados. Cada linha corresponde a uma das áreas descritas acima, sempre com mensagem correspondente e um espaço entre os dois pontos e o valor. O valor calculado deve ser apresentado com 3 dígitos após o ponto decimal.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|3.0 4.0 5.2                                |TRIANGULO: 7.800                         |
|                                           |CIRCULO: 84.949                          |
|                                           |TRAPEZIO: 18.200                         |
|                                           |QUADRADO: 16.000                         |
|                                           |RETANGULO: 12.000                        |
|12.7 10.4 15.2                             |TRIANGULO: 96.520                        |
|                                           |CIRCULO: 725.833                         |
|                                           |TRAPEZIO: 175.560                        |
|                                           |QUADRADO: 108.160                        |
|                                           |RETANGULO: 132.080                       |

## Resposta

V = input().split()

TRIANGULO = (float(V[0]) * float(V[2]))/2

CIRCULO = 3.14159 * float(V[2]) ** 2

TRAPEZIO = (float(V[0]) + float(V[1])) * float(V[2]) / 2

QUADRADO = float(V[1])**2

RETANGULO = float(V[0]) * float (V[1])

print("TRIANGULO: {:.3f}".format(TRIANGULO))

print("CIRCULO: {:.3f}".format(CIRCULO))

print("TRAPEZIO: {:.3f}".format(TRAPEZIO))

print("QUADRADO: {:.3f}".format(QUADRADO))

print("RETANGULO: {:.3f}".format(RETANGULO))