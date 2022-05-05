# Lógica de Programação Essencial

## O que é um algoritimo?

É uma sequência de passos que resolve um problema.

## Exemplo de algoritimo

início-dia

Acordei

Levantei

Troquei de roupa

Escovei os dentes

Fui a padaria

Tomei café

Escovei os dentes

Fui ao trabalho

...

# Pseudocódigo

## O que é um pseudocódigo?

Pseudocódigo é uma forma genérica de escrever um algoritimo, utilizando uma linguagem simples(nativa, ou seja, em português a quem o escreve, de forma a ser entendida por qualquer pessoa).

# Variáveis e Constantes

## O que são variáveis?

Na programação, uma variável é um objeto(uma posição, frequntemente localizada na memória) capaz de reter e representar um valor ou expressão.

É um dado na memória do computador que pode ser alterado durante a execução do algoritimo.

## O que é uma constante?

As constantes são valores imutáveis e não são alterados durante a vida útil do programa.

### Declaração de variáveis

DECLARA nota1: número

DECLARA nota2: número

DECLARA nota3: número

DECLARA media : (nota1 + nota2 + nota3)/3

A declaração para constantes é a mesma mas não serão alterados ao longo

da execução do programa.

# Fluxograma

## O que é um fluxograma?

Um floxugrama é um tipo de diagrama e pode ser entendido como uma representação esquemática de um processo. Podemos entendê-lo na prática, como a documentação dos passos necessários para a execução de um processo qualquer.

## Exemplo:

![fluxo grama](https://lh6.googleusercontent.com/HfQ3Czrf1BgHGJcBktVF3AhSV6OWb912-LAcMHss013gP_-eFvctXqzulRThqlqGWB4ftvlqy3e0vX37he2PjAirROR3kI9eODFAQQFDWNE-sN4CbkLG4AmhU30LshqiJLBDwBrz)

## Diagrama de blocos

Utilizado para representar o método do fluxugrama.

##### Simbolos e exemplos em [Simbologia de um Fluxograma](https://www.lucidchart.com/pages/pt/fluxograma-simbologia).

## Exemplo com declarações:

![](https://dkrn4sk0rn31v.cloudfront.net/uploads/2020/11/Declara%C3%A7%C3%A3o-de-vari%C3%A1veis-simples.png)

# Expressões aritméticas

São expressões que utilizam operadores aritiméticos e funções aritiméticas envolvendo contantes e variáveis.

Exemplo:

50+50

total + 50

## Operadores aritiméticos

![operadores aritmeticos](https://1.bp.blogspot.com/-7VlmTNSM1SY/WwsXyitzclI/AAAAAAAADpU/6-8hgGZsICcx6z1n8tWt6IjXhlTqwCqMwCLcBGAs/s400/Sem%2Bt%25C3%25ADtulo1.png)

# Expressões literais

São expressões com constantes e/ou variáveis que tem como resultado valores literais. Iremos utilizar as expressões literais na atribuição de valor para uma variável ou constante.

Exemplo:

nome = "José da Silva"

media = (nota1+nota2)/2

## Expressões relacionais

São expressões compostas por outras expressões ou variáveis com operadores relacionais.

As expressões relacionais retornam valores lógicos(verdadeiro/falso).

![operadores relacionis](https://slideplayer.com.br/slide/337889/1/images/2/Operadores+Relacionais.jpg)

# Tomadas de Decisão

Quando escrevemos programas, geralmente ocorre a necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução.

![Estruturas condicionais e de repetição | Blog TreinaWeb](https://dkrn4sk0rn31v.cloudfront.net/uploads/2020/10/Estrutura-Condicional-Simples.png)

# Concatenção

Concatenção é um termo usado em computação para designar a operação de unir o conteúdo de duas strings.

String é uma sequncia de caracteres.

Agrupamento de duas ou mais células que, incluindo fórmulas , textos ou outras informações contida no seu interior, dá origem a um único resultado.

### Exemplo:

nome = "Julio"

sobrenome = " Alves"

### Dependendo da linguagem de programação para concatenar usamos (+), (&) ou (,).

nome completo = nome + sobrenome

nome completo = nome & sobrenome

nome completo = nome, sobrenome

ou seja

nome completo =  "Julio Alves""



# Estrutura de repetição

Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.

##### Exemplo:

![exemplo de repetições com fluxograma](https://dkrn4sk0rn31v.cloudfront.net/uploads/2020/10/ENQUANTO-FOR.png)

**Enquanto** a variável **i** for menor que 10 exibirá 9 x **i** = (9 * **i**) e depois somará **i** com 1 até que **i** seja maior que 10 e finalizar.



# Linguagens de Programação

Linguagem de programação é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (software). Um software pode ser desenvolvido para rodar em um computador, dispositivo móvel ou em qualquer equipamento que permita sua execução.



A função das linguagens de programação é servir como meio de comunicação entre computadores e humanos.



## A linguagens de baixo e alto nível

### Alto nível:

Essas são aquelas cuja sintaxe se aproxima mais da nossa linguagem e se distanciam mais da linguagem de máquina.

### Baixo nível:

É aquela que si aproxima mais da linguagem de máquina. Essas são as que você precisa ter o conhecimento direto da arquitetura do computador para fazer alguma coisa.



## Compiladas ou interpretadas

### Compiladas:

É uma linguem de programção em que o código fonte, é executado ditetamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação.

### Interpretadas:

É uma linguagem de programaçao em que o código fonte é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador.



# Desvios Condicionais

## se

É utilizada a palavra reservada **se**, a condição a ser tratada entre parenteses e as intruções que devem ser executadas entre chaves caso o desvio seja verdadeiro.

## se-senao

Caso na condição **se** o desvio seja falso um outro conjunto de comandos pode ser executado.

### Exemplo em portugol:

```javascript
se(media>=7){

        escreva("Parabéns!! Você foi aprovado!!")

}

senao{

        escreva("Infelizmente você foi reprovado")

}
```



## Portugol

O [Portugol]([Portugol Studio](http://lite.acad.univali.br/portugol/)) é uma pseudo-**linguagem** algorítmica muito utilizada na descrição de algoritmos, destaca-se pelo uso de comandos em português, o que facilita o aprendizado da lógica de programação, habituando o iniciante com o formalismo de programação.



## Caso

Este comando é similar aos comandos **se** e **senão**, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o **se**, ele possui algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos.

### Exemplo em portugol:

```javascript
inteiro menu = 0

escolha(menu) // Valor a ser testado
{
    caso 1: //teste se é igual a 1
    escreva("OK! Abrir Netflix!!")
    pare
    caso 2: //teste se é igual a 2
    escreva("OK! Abrir Amazon Prime!!")
    pare
    caso 3: //teste se é igual a 3
    escreva("OK! Abrir HBO GO!!!")
    pare
}
```

## Repetições em pseudocódigo

### Exemplo em portugol:

```javascript
inteiro contador = 0
inteiro limite = 0
inteiro resultado = 0

faca{
    resultado = 9 * contador
    escreva("9 X " + contador + " = " + resultado + "\n")
    // \n e um comando para pular uma linha.
}enquanto(contador <= limite)
```



# Vetores e Matrizes

Uma **matriz** é uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória.

A invidualização de cada variável de um vetor é feita através do uso de **índices**.

Os **vetores** são matrizes de uma só dimensão.

## Exemplo vetor em portugol:

```javascript
cadeia frutas[5] //Declara um vetor de 5 posições

frutas[0] = "Maça"
frutas[1] = "Pera"
frutas[2] = "Uva"
frutas[3] = "Melão"
frutas[4] = "Banana"
```

## Exemplo matriz em portugol:

```javascript
//Declarando matriz com 2 vetores com 3 posições
cadeia cesta[][] = {{"Maça", "100"}, {"Pera", "200"}, {"Melão", "300"}}
```
