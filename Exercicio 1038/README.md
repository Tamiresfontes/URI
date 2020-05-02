# Lanche

Com base na tabela abaixo, escreva um programa que leia o código de um item e a quantidade deste item. A seguir, calcule e mostre o valor da conta a pagar.

|    CÓDIGO     |    ESPECIFICAÇÃO     |  PREÇO  |
|:-------------:|:--------------------:|:-------:|
|       1       |     Cachorro quente  |  R$4,00 |
|       2       |     X-Salada         |  R$4,50 |
|       3       |     X-Bacon          |  R$5,00 |
|       4       |     Torrada Simples  |  R$2,00 |
|       5       |     Refrigerante     |  R$1,50 |

## Entrada

O arquivo de entrada contém dois valores inteiros correspondentes ao código e à quantidade de um item conforme tabela acima.


## Saída

O arquivo de saída deve conter a mensagem "Total: R$ " seguido pelo valor a ser pago, com 2 casas após o ponto decimal.

## Resposta

preço = input().split()

A,B= preço

if A == "1":

    print("Total: R$ {:.2F}".format(4.00*float(B)))

if A == "2":

    print("Total: R$ {:.2F}".format(4.50*float(B)))

if A == "3":

    print("Total: R$ {:.2F}".format(5.00*float(B)))

if A == "4":

    print("Total: R$ {:.2F}".format(2.00*float(B)))

if A == "5":

    print("Total: R$ {:.2F}".format(1.50*float(B)))