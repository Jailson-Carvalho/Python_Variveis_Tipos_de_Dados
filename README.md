# Módulo 01 | Python: Variáveis & Tipos de Dados

## Descrição

Este repositório contém o material didático e os exemplos práticos do primeiro módulo do curso de Python, ministrado pelo professor Jailson Carvalho. O módulo foca no entendimento de variáveis, tipos de dados básicos e operações essenciais em Python, que são a base para o desenvolvimento de programas mais avançados.

## Tópicos Abordados

1. **Introdução ao Google Colab**
2. **Variáveis**
   - Definição e tipos nativos
   - Operações básicas
3. **Números**
   - Tipos numéricos: inteiros (int), decimais (float) e complexos
   - Operações e conversão entre tipos
4. **Strings**
   - Definição e operações
   - Métodos úteis para manipulação de strings
5. **Booleanos**
   - Definição, operações lógicas e conversão entre tipos

## Objetivo

Este módulo tem como objetivo ensinar os conceitos fundamentais de programação em Python, focando na manipulação de variáveis e tipos de dados como números, strings e valores booleanos. Além disso, serão abordadas as operações básicas para manipular esses dados e como realizar conversões entre tipos.

## Estrutura do Módulo

### 1. Introdução ao Google Colab
- Demonstração de como utilizar o Google Colab como ambiente de desenvolvimento.

### 2. Variáveis
- **Definição**: Mecanismo de armazenamento volátil de dados na memória do computador.
- **Tipos Nativos**:
  - Tipos numéricos: `int`, `float`, `complex`
  - Tipos de texto: `str`
  - Tipos lógicos: `bool`
  - Tipo vazio: `NoneType`
  
### 3. Números
- **Motivação**: Exemplo prático sobre o cálculo de ticket médio diário de um restaurante.
- **Operações**: Implementação das quatro operações matemáticas e operações avançadas como divisão inteira, potência e resto de divisão.
- **Conversão entre tipos**: Como transformar valores entre `int`, `float` e `complex`.

### 4. Strings
- **Motivação**: Comparação e normalização de dados de latitude e longitude em diferentes formatos.
- **Operações**: Concatenar strings, fatiamento (slicing) e extração de substrings.
- **Métodos**: Manipulação de strings utilizando métodos nativos como `upper()`, `find()`, e `replace()`.

### 5. Booleanos
- **Motivação**: Comparação de strings de usuário e senha para controle de acesso.
- **Operações lógicas**: Operadores `or`, `and` e `not` e como trabalhar com valores booleanos.
- **Conversão**: Como converter tipos numéricos e strings para booleanos utilizando `bool()`.

## Exemplos

Aqui estão alguns exemplos de código fornecidos no material:

### 1. Exemplos com Variáveis
```python
idade = 33
print(idade)

nome = 'Jailson Carvalho'
print(nome)
```

### 2. Exemplos com Números
```python
preco = 1000
print(type(preco))

preco = 0.05
print(type(preco))

total_a_pagar = preco * 0.557
print(f'Total a ser pago: R$ {total_a_pagar:.2f}')
```

### 3. Exemplos com Strings
```python
nome = 'José Jailson'
sobrenome = 'de Carvalho'
apresentacao = f'Olá, meu nome é {nome} {sobrenome}.'
print(apresentacao)
```

### 4. Exemplos com Booleanos
```python
saldo_em_conta = 200
valor_do_saque = 100
pode_executar_saque = saldo_em_conta >= valor_do_saque
print(pode_executar_saque)
```

## Como Utilizar

Este módulo pode ser explorado de duas maneiras:
1. **Prática**: Execute os exemplos de código diretamente no seu ambiente Python, seja no Google Colab ou em qualquer outro editor de sua escolha.
2. **Estudo**: Leia os tópicos e absorva os conceitos, reforçando com os exemplos práticos.

Para quem está iniciando, é recomendado experimentar cada conceito diretamente, modificando as variáveis e observando os resultados.

## Licença

Este material é fornecido sob a licença [MIT](https://opensource.org/licenses/MIT). Sinta-se à vontade para utilizar, modificar e compartilhar de acordo com os termos dessa licença.

---

**Estudante Jailson Carvalho**
