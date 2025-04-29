# aulas-python

![ilustração linguagem python](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Kuki_2005.jpg/250px-Kuki_2005.jpg)

## Tipos primitivos: string, number (int/float), boolean;

Para saber mais, [clique aqui](https://dev.to/dormin/tipos-primitivos-em-python-10jg)

### Operadores aritméticos;
#### Operadores lógicos/comparativos;
#### Estruturas condicionais (if/elif/else)

**Tipos de estruturas condicionais:**

- if: Executa um bloco de código se uma condição especificada for verdadeira.
- elif: Significa "Else if" e permite que você verifique várias condições.
- else: Executa um bloco de código se nenhuma das condições anteriores for verdadeira.

``` py
participante = int(input('Qual a sua idade? '))
acompanhante = int(input('Qual a sua idade? '))

if participante >= 18 and acompanhante >= 18:
  print('Pode entrar.')
elif participante >= 15 and acompanhante >= 18:
    print('Pode entrar.')
else:
  print('Não pode entrar.')
```
``` py
a = int(input('Digite o comprimento do primeiro lado: '))
b = int(input('Digite o comprimento do segundo lado: '))
c = int(input('Digite o comprimento do terceiro lado: '))

if (a + b < c) and (a + c < b) and (b + c < a):
  print('Não é um triângulo.')
elif a == b == c:
  print('É um triângulo equilátero.')
elif a == b or a == c or b == c:
  print('É um triângulo isósceles.')
else:
  print('É um triângulo escaleno.')
```
