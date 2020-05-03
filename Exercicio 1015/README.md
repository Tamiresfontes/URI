# Distância entre dois pontos

Leia os quatro valores correspondentes aos eixos x e y de dois pontos quaisquer no plano, p1(x1,y1) e p2(x2,y2) e calcule a distância entre eles, mostrando 4 casas decimais após a vírgula, segundo a fórmula:

*Distância: √(x2 - x1)² + (y2 - y1)²*

## Entrada

O arquivo de entrada contém duas linhas de dados. A primeira linha contém dois valores de ponto flutuante: *x1 y1* e a segunda linha contém dois valores de ponto flutuante *x2 y2*.

## Saída

Calcule e imprima o valor da distância segundo a fórmula fornecida, com 4 casas após o ponto decimal.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|1.0 7.0                                    |4.4721                                   |
|5.0 9.0                                    |                                         |
|-2.5 0.4                                   |16.1484                                  |
|12.1 7.3                                   |                                         |
|2.5 -0.4                                   |16.4575                                  |
|-12.2 7.0                                  |                                         |

## Resposta

p1 = input().split()

p2 = input().split()

D= ( (float(p2[0]) - float(p1[0])) **2 + (float(p2[1])- float(p1[1])) **2 ) ** (1/2)

print("{:.4F}".format(D))