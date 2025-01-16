# Iniciando no python
<h6 style="text-align:right;">Bases para aprofundamento</h6>

---

## 1. O Início

De começo um clássico:

```
print ("Hello World!")
```

Essa função demonstra uma impressão de texto básica em console, na qual se apresenta aquilo indicado dentro dos parênteses '( )' em console, tendo assim a seguinte apresentação

>Hello World!


## 2. Operadores matemáticos


### 2.1 - Adição
Adição é a operação matemática de somar dois ou mais números. Em Python, você pode usar o operador '+' para somar dois valores. Por exemplo:
```
1 + 1
```
Obtém-se a saída:
>2

### 2.2 - Subtração
Subtração é a operação matemática de diminuir um ou mais números de outro. Em Python, você pode usar o operador '-' para subtrair um valor de outro. Por exemplo:
```
5 - 3
```
Obtém-se a saída:
>2


### 2.3 - Multiplicação
Multiplicação é a operação matemática de multiplicar dois ou mais números. Em Python, você pode usar o operador '*' para multiplicar dois valores. Por exemplo:
```
2 * 3
```
Obtém-se a saída:
>6

### 2.4 - Divisão
Divisão é a operação matemática de dividir um número por outro. Em Python, você pode usar o operador '/' para dividir dois valores. Por exemplo:
```
6 / 2
```
Obtém-se a saída:
>3


### 2.5 - Potenciação
Potenciação é a operação matemática de elevar um número a uma determinada potência. Em Python, você pode usar o operador '**' para elevar um valor a uma potência. Por exemplo:
```
2 ** 3
```
Obtém-se a saída:
>8


### 2.6 - Módulo
Módulo é a operação matemática de encontrar o resto da divisão de um número por outro. Em Python, você pode usar o operador '%' para obter o resto da divisão. Por exemplo:
```
10 % 3
```
Obtém-se a saída:
>1


## 3. Variáveis

Variáveis são usadas para armazenar valores que podem ser referenciados e manipulados posteriormente no código. Em Python, você pode criar uma variável simplesmente atribuindo um valor a um nome usando o operador '='. Por exemplo:
```
x = 5
y = "Olá, Mundo!"
```
Aqui, `x` é uma variável que armazena `5`, e `y` é uma variável que armazena  `"Olá, Mundo!"`.

### 3.1 - Nomenclatura de variáveis:
Para nomear variáveis em Python, é recomendado seguir as convenções do guia de estilo oficial para Python(PEP 8). Uma dessas convenções é o uso do snake_case.

<h5 style="text-align:center;">Snake Case</h5>
No snake_case, todas as letras são minúsculas e as palavras são separadas por underscores (_). Por exemplo:

```
idade_do_usuario = 25
nome_completo = "João da Silva"
numero_de_itens = 10
```

<h5 style="text-align:center;">Regras Gerais para nomear Variáveis</h5>

* Comece com uma letra ou underscore (_): Não pode começar com um número.
* Use letras, números e underscores: Não use espaços ou caracteres especiais.
* Seja descritivo: Escolha nomes que descrevam claramente o propósito da variável.
* Evite palavras reservadas: Não use palavras que são reservadas pela linguagem Python (como class, def, return, etc.)

### 3.2 - Tipos de variáveis:

Em Python, as variáveis podem armazenar diferentes tipos de dados. Cada tipo de variável tem suas próprias características e usos específicos, permitindo que você escolha o tipo mais adequado para cada situação no seu código.

##### 3.2.1 - Números Inteiros (int)
Números inteiros são números sem parte decimal. Eles podem ser positivos ou negativos. Exemplo:
```
idade = 30
saldo_bancario = -20
```
Obtém-se a saída:
>30
>
>-20

##### 3.2.2 - Ponto Flutuante ou Decimal (float)
Números de ponto flutuante são números com parte decimal. Eles são usados para representar valores que não são inteiros. Exemplo:
```
altura = 1.75
troco = 3.45
```
Obtém-se a saída:
>1.75
>
>3.45

##### 3.2.3 - Strings (str)
Strings são sequências de caracteres usadas para representar texto. Elas são delimitadas por aspas simples ou duplas. Exemplo:
```
nome = "Ana"
slogan = 'Ao infinito e além!'
```
Obtém-se a saída:
>"Ana"
>
>'Ao infinito e além!'

##### 3.2.4 - Booleanos (bool)
Booleanos são valores lógicos que podem ser `True` (Verdadeiro ou `1`) ou `False` (Falso ou `0`). Eles são usados para representar estados binários. Exemplo:
```
ativo = True
```
Obtém-se a saída:
>True

##### 3.2.5 - Listas (list)
Listas são coleções ordenadas de valores que podem ser de tipos diferentes. Elas são delimitadas por colchetes e os elementos são separados por vírgulas. Exemplo:
```
frutas = ["maçã", "banana", "laranja"]
historico_saldo = [10 , 7.50 , 45]
```
Obtém-se a saída:
>["maçã", "banana", "laranja"]
>
>[10, 7.50, 45]

##### 3.2.6 - Dicionários (dict)
Dicionários são coleções de pares chave-valor. Eles são delimitados por chaves e cada par é separado por dois pontos. Exemplo:
```
ficha_de_personagem = {"nome": "Carlos", "idade": 28 , "Coragem": True}
```
Obtém-se a saída:
>{"nome": "Carlos", "idade": 28, "Coragem": True}

##### 3.2.7 - Tuplas (tuple)
Tuplas são coleções ordenadas e imutáveis de valores. Elas são delimitadas por parênteses e os elementos são separados por vírgulas. Exemplo:
```
coordenadas = (10.0, 20.0)
```
Obtém-se a saída:
>(10.0, 20.0)

##### 3.2.8 - Conjuntos (set)
Conjuntos são coleções não ordenadas de valores únicos. Eles são delimitados por chaves e os elementos são separados por vírgulas. Exemplo:
```
numeros_unicos = {1, 2, 3, 4, 5}
```
Obtém-se a saída:
>{1, 2, 3, 4, 5}
##### 3.2.9 - Números Complexos (complex)
Números complexos são números que possuem uma parte real e uma parte imaginária. Em Python, você pode criar números complexos usando a notação `a + bj`, onde `a` é a parte real e `b` é a parte imaginária. Exemplo:
```
numero_complexo = 3 + 4j
```
Obtém-se a saída:
> (3+4j)


