# Projeto Python: Guia Básico

## Introdução

Este projeto foi desenvolvido com o objetivo de ensinar os primeiros passos na construção de um projeto em **Python**. Python é uma linguagem de programação popular devido à sua simplicidade e versatilidade, sendo amplamente usada para automação, análise de dados, desenvolvimento web, e muito mais.

## Estrutura do Projeto

Ao construir um projeto em Python, é importante organizar seus arquivos e diretórios de forma clara. Uma estrutura básica de projeto pode ser assim:


- `src/main.py`: O arquivo principal que contém a lógica do seu código.
- `requirements.txt`: Arquivo que lista as dependências do seu projeto (bibliotecas externas).

## Sintaxe Básica do Python

Python possui uma sintaxe simples e fácil de entender. Aqui estão alguns conceitos básicos da linguagem:

```python
# Exemplo de declaração de variáveis
nome = "Rafael"
idade = 30
altura = 1.75

# Exemplo de estrutura condicional
if idade >= 18:
    print("Você é maior de idade.")
else:
    print("Você é menor de idade.")

# Exemplo de laço 'for'
for i in range(5):
    print(i)

# Exemplo de laço 'while'
contador = 0
while contador < 5:
    print(contador)
    contador += 1

# Exemplo de função
def saudacao(nome):
    return f"Olá, {nome}!"

print(saudacao("Rafael"))


# Este README apresenta uma introdução simples sobre como estruturar um projeto Python, junto com explicações básicas de sintaxe e exemplos de código. Você pode personalizá-lo conforme o seu projeto!

