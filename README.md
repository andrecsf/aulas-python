# aulas-python

![ilustração linguagem python](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Kuki_2005.jpg/250px-Kuki_2005.jpg)
![ilustração linguagem python]("E:\Aluno\Pictures\Screenshots\Captura de tela 2025-05-13 110345.png")

## Tipos primitivos: string, number (int/float), boolean;

Para saber mais, [clique aqui](https://dev.to/dormin/tipos-primitivos-em-python-10jg)

### Operadores aritméticos;

(+) : adição → 2 + 3 resulta em 5

(-) : subtração → 5 - 2 resulta em 3

(*) : multiplicação → 4 * 3 resulta em 12

/ : divisão (retorna float) → 10 / 2 resulta em 5.0

// : divisão inteira (descarta a parte decimal) → 7 // 2 resulta em 3

% : módulo (resto da divisão) → 7 % 3 resulta em 1

** : exponenciação → 2 ** 3 resulta em 8

Exemplo:
``` py
# Definindo dois números
a = 10
b = 3

# Operadores aritméticos
soma = a + b           # Adição
subtracao = a - b      # Subtração
multiplicacao = a * b  # Multiplicação
divisao = a / b        # Divisão (float)
div_inteira = a // b   # Divisão inteira
modulo = a % b         # Módulo (resto)
exponenciacao = a ** b # Exponenciação

# Exibindo os resultados
print("Soma:", soma)
print("Subtração:", subtracao)
print("Multiplicação:", multiplicacao)
print("Divisão:", divisao)
print("Divisão inteira:", div_inteira)
print("Módulo:", modulo)
print("Exponenciação:", exponenciacao)
```


#### Operadores lógicos/comparativos;

##### Operadores Comparativos
#### Usados para comparar valores; retornam True ou False.

== : igual a → 5 == 5 é True

!= : diferente de → 5 != 3 é True

(>) : maior que → 7 > 2 é True

< : menor que → 3 < 5 é True

(>=) : maior ou igual a → 5 >= 5 é True

<= : menor ou igual a → 4 <= 6 é True

Operadores Lógicos
Usados para combinar expressões booleanas.

and : retorna True se ambas forem verdadeiras
→ True and False é False

or : retorna True se pelo menos uma for verdadeira
→ True or False é True

not : inverte o valor lógico
→ not True é False

Exemplo:
``` py
# Variáveis de exemplo
x = 10
y = 5

# Operadores comparativos
print("x == y:", x == y)     # False
print("x != y:", x != y)     # True
print("x > y:", x > y)       # True
print("x < y:", x < y)       # False
print("x >= y:", x >= y)     # True
print("x <= y:", x <= y)     # False

# Operadores lógicos
a = x > y     # True
b = x == y    # False

print("a and b:", a and b)   # False
print("a or b:", a or b)     # True
print("not a:", not a)       # False
print("not b:", not b)       # True

```

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
