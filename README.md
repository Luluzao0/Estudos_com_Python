# README - Estudos em Python

TODOS os codigos estao dentro do arquivo .ipynb que pode ser aberto tanto em IDE's como no proprio google Colab(onde foi feito)
Este README destina-se a documentar meus estudos e ajudar jovens iniciantes na carreira de programação em Python, abordando vários tópicos essenciais para quem deseja aprender a programar nessa linguagem versátil. Ao longo deste documento, você encontrará uma breve visão geral de cada tópico que estudei.

## Índice

1. [Variáveis e o Comando de Atribuição](#variáveis-e-o-comando-de-atribuição)
2. [Comandos de Repetição](#comandos-de-repetição)
3. [Uso de if, if-else, if-elif-else](#uso-de-if-if-else-if-elif-else)
4. [Indicadores de Passagem](#indicadores-de-passagem)
5. [Repetição Encaixada](#repetição-encaixada)
6. [Funções em Python](#funções-em-python)
7. [Listas](#listas)
8. [Funções com Listas](#funções-com-listas)
9. [Strings](#strings)
10. [Strings NÃO São Listas](#strings-não-são-listas)
11. [Tabela ASCII, Caracteres](#tabela-ascii-caracteres)
12. [Arquivos](#arquivos)
13. [Matrizes](#matrizes)
14. [Otimizando Seu Código com Algoritmos de Busca](#otimizando-seu-código-com-algoritmos-de-busca)
15. [Algoritmos Elementares de Ordenação](#algoritmos-elementares-de-ordenação)

---

## Variáveis e o Comando de Atribuição

Neste tópico, aprendi como declarar variáveis em Python e como usar o comando de atribuição para armazenar valores em variáveis. Python é uma linguagem de tipagem dinâmica, o que significa que as variáveis podem armazenar diferentes tipos de dados.

```python
# Exemplo de variáveis e atribuição
nome = "Luis"
idade = 20
```

## Comandos de Repetição

Comandos de repetição, como `for` e `while`, são fundamentais para automatizar tarefas e processar dados em Python. Eles permitem a execução repetida de um bloco de código.

```python
# Exemplo de um loop for
for i in range(5):
    print(i)
```

## Uso de if, if-else, if-elif-else

Os comandos condicionais `if`, `if-else` e `if-elif-else` permitem tomar decisões em seu código com base em condições. Eles são úteis para controlar o fluxo de execução do programa.

```python
# Exemplo de if-else
idade = 20
if idade >= 18:
    print("Pode votar!")
else:
    print("Ainda não pode votar.")
```

## Indicadores de Passagem

Indicadores de passagem, como `break` e `continue`, permitem controlar a execução de loops. O `break` encerra o loop, enquanto o `continue` pula a iteração atual e continua para a próxima.

```python
# Exemplo de uso do break
for i in range(10):
    if i == 5:
        break
    print(i)
```

## Repetição Encaixada

Repetição encaixada envolve a utilização de loops dentro de outros loops. Isso é útil para lidar com estruturas de dados multidimensionais e problemas complexos.

```python
# Exemplo de repetição encaixada
for i in range(3):
    for j in range(2):
        print(i, j)
```

## Funções em Python

Funções são blocos de código reutilizáveis que permitem organizar seu código de maneira modular. Python fornece uma maneira fácil de definir e chamar funções.

```python
# Exemplo de definição e chamada de função
def saudacao(nome):
    print(f"Olá, {nome}!")

saudacao("Maria")
```

## Listas

Listas são estruturas de dados que permitem armazenar múltiplos valores em uma única variável. Elas são mutáveis e podem conter diferentes tipos de dados.

```python
# Exemplo de lista
frutas = ["morango", "melancia", "laranja"]
```

## Funções com Listas

Você pode realizar várias operações em listas, como adição, remoção e ordenação de elementos. Python oferece funções integradas para facilitar essas tarefas.

```python
# Exemplo de operações em listas
numeros = [3, 1, 4, 1, 5, 9, 2]
numeros.sort()
```

## Strings

Strings são sequências de caracteres e são amplamente usadas em Python. Você pode manipular strings de várias maneiras, como concatenação e indexação.

```python
# Exemplo de manipulação de strings
nome = "L"
sobrenome = "Luis"
nome_completo = nome + " " + sobrenome
```

## Strings NÃO São Listas

Embora as strings sejam semelhantes a listas de caracteres, elas são imutáveis em Python. Isso significa que você não pode modificar caracteres individuais de uma string.

```python
# Exemplo de tentativa de modificação de uma string (erro)
texto = "Olá, Mundo!"
texto[0] = "H"  # Isso gera um erro
```

## Tabela ASCII, Caracteres

A tabela ASCII contém mapeamentos de caracteres para valores numéricos. Você pode usar esses valores para realizar operações com caracteres em Python.

```python
# Exemplo de uso da tabela ASCII
caractere = 'A'
valor_ascii = ord(caractere)
```

## Arquivos

Python oferece facilidades para trabalhar com arquivos, permitindo a leitura e escrita de dados em diferentes formatos. É importante garantir que os arquivos sejam abertos e fechados corretamente.

```python
# Exemplo de leitura de um arquivo
with open("arquivo.txt", "r") as arquivo:
    conteudo = arquivo.read()
```

## Matrizes

Matrizes são estruturas bidimensionais que podem ser representadas como listas de listas em Python. Elas são úteis para armazenar dados tabulares.

```python
# Exemplo de matriz
matriz = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
```

## Otimizando Seu Código com Algoritmos de Busca

Algoritmos de busca, como pesquisa linear e pesquisa binária, são essenciais para encontrar elementos em listas

 ou matrizes de maneira eficiente. Eles ajudam a otimizar o desempenho do seu código.

```python
# Exemplo de pesquisa linear
def pesquisa_linear(lista, alvo):
    for i, elemento in enumerate(lista):
        if elemento == alvo:
            return i
    return -1
```

## Algoritmos Elementares de Ordenação

Algoritmos de ordenação, como o algoritmo de seleção e o algoritmo de bolha, são usados para organizar elementos em ordem crescente ou decrescente. Eles são cruciais para lidar com dados não ordenados.

```python
# Exemplo de algoritmo de seleção
def selecao_ordenada(lista):
    for i in range(len(lista)):
        menor_idx = i
        for j in range(i+1, len(lista)):
            if lista[j] < lista[menor_idx]:
                menor_idx = j
        lista[i], lista[menor_idx] = lista[menor_idx], lista[i]
```

Estes são os principais tópicos que estudei em Python. Cada tópico é uma base sólida para construir suas habilidades de programação em Python.
