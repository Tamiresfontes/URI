# Conversão de tempo

Leia um valor inteiro, que é o tempo de duração em segundos de um determinado evento em uma fábrica, e informe-o expresso no formato horas:minutos:segundos.

## Entrada

O arquivo de entrada contém um valor inteiro N.

## Saída

Imprima o tempo lido no arquivo de entrada (segundos), convertido para horas:minutos:segundos, conforme exemplo fornecido.

## Resposta

S = int(input())

HORAS = S // 3600

S = S - (HORAS * 3600)

MINUTOS = S // 60

S = S - (MINUTOS * 60)

SEGUNDOS = S

print("{:.0F}:{:.0F}:{:.0F}".format(HORAS,MINUTOS,SEGUNDOS))