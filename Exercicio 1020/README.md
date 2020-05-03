# Idade em dias

Leia um valor inteiro correspondente à idade de uma pessoa em dias e informe-a em anos, meses e dias

Obs.: apenas para facilitar o cálculo, considere todo ano com 365 dias e todo mês com 30 dias. Nos casos de teste nunca haverá uma situação que permite 12 meses e alguns dias, como 360, 363 ou 364. Este é apenas um exercício com objetivo de testar raciocínio matemático simples.

## Entrada

O arquivo de entrada contém um valor inteiro.

## Saída

Imprima a saída conforme exemplo fornecido.

|           **Exemplo de entrada**          |           **Exemplo de saída**          |
|:-----------------------------------------:|:---------------------------------------:|
|400                                        |1 ano (s)                                |
|                                           |1 mes(es)                                |
|                                           |5 dia(s)                                 |
|800                                        |2 ano (s)                                |
|                                           |2 mes(es)                                |
|                                           |10 dia(s)                                |
|30                                         |0 ano (s)                                |
|                                           |1 mes(es)                                |
|                                           |0 dia(s)                                 |

## Resposta


D = int(input())

ANOS = D // 365

D = D - ANOS * 365

MESES = D // 30

D = D - MESES * 30

DIAS = D

print("{:.0F} ano(s)".format(ANOS))

print("{:.0F} mes(es)".format(MESES))

print("{:.0F} dia(s)".format(DIAS))