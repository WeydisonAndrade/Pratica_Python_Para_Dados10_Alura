# Pratica_Python_Para_Dados10_Alura

# 📘 Tratamento de Exceções em Python para Ciência de Dados

Este repositório reúne exercícios práticos desenvolvidos em Python com foco em tratamento de exceções, validação de dados e manipulação de estruturas utilizadas em projetos de análise de dados.

Os programas simulam situações reais encontradas em ciência de dados, processamento de linguagem natural (NLP), correção automatizada de provas, validação de entradas e processamento de experimentos laboratoriais.

---

# 🎯 Objetivos do Projeto

Os exercícios foram desenvolvidos para praticar:

* Tratamento de exceções em Python
* Estruturas `try`, `except` e `finally`
* Validação de entradas
* Manipulação de listas e dicionários
* Criação de funções
* Processamento de dados
* Estruturas condicionais
* Verificação de inconsistências
* Pensamento computacional
* Programação defensiva
* Processamento de linguagem natural (NLP)

---

# 🚀 Programas Desenvolvidos

## 1️⃣ Divisão entre Números Float com Tratamento de Erros

### 📖 Descrição

Este programa solicita dois números decimais para realizar uma divisão.

O sistema trata possíveis erros de entrada, como divisão por zero e inserção de caracteres inválidos.

### 🎯 Conceitos trabalhados

* Conversão de tipos
* Estrutura `try-except`
* `ZeroDivisionError`
* `ValueError`
* Formatação de saída

### ✅ Funcionalidades

* Realiza divisão entre números float
* Detecta divisão por zero
* Detecta entradas textuais inválidas
* Exibe mensagens de erro amigáveis

---

## 2️⃣ Busca de Dados em Dicionários

### 📖 Descrição

O programa realiza a busca da idade de uma pessoa em um dicionário.

Caso o nome informado não exista, o sistema utiliza tratamento de exceção para evitar falhas.

### 🎯 Conceitos trabalhados

* Dicionários
* Busca por chave
* `KeyError`
* Tratamento de exceções

### ✅ Funcionalidades

* Consulta de dados por chave
* Validação de existência da chave
* Mensagem personalizada de erro

---

## 3️⃣ Conversão de Valores para Float

### 📖 Descrição

Este exercício cria uma função responsável por converter todos os elementos de uma lista para o tipo float.

O programa identifica valores inválidos e utiliza a cláusula `finally` para finalizar a execução da função.

### 🎯 Conceitos trabalhados

* Funções
* Conversão de tipos
* List comprehension
* `ValueError`
* `finally`

### ✅ Funcionalidades

* Conversão automática de dados
* Tratamento de valores inválidos
* Encerramento seguro da função

---

## 4️⃣ Agrupamento de Listas em Tuplas

### 📖 Descrição

O sistema recebe duas listas e agrupa os elementos correspondentes em tuplas.

Cada tupla contém:

* valor da primeira lista
* valor da segunda lista
* soma dos valores

Também são realizadas validações de tamanho das listas e compatibilidade entre os dados.

### 🎯 Conceitos trabalhados

* Funções
* Tuplas
* `zip()`
* `IndexError`
* `TypeError`
* Validação de dados

### ✅ Funcionalidades

* Agrupamento de elementos
* Soma automática de valores
* Verificação de listas com tamanhos diferentes
* Tratamento de tipos incompatíveis

---

## 5️⃣ Correção Automática de Provas

### 📖 Descrição

Este programa simula um sistema de correção automática de testes objetivos.

O sistema compara as respostas dos estudantes com um gabarito oficial e calcula automaticamente a pontuação.

Caso exista alguma alternativa inválida, uma exceção personalizada é lançada.

### 🎯 Conceitos trabalhados

* Listas aninhadas
* Estruturas de repetição
* Comparação de dados
* `ValueError`
* Processamento de respostas

### ✅ Funcionalidades

* Correção automática de provas
* Cálculo de notas
* Verificação de alternativas válidas
* Identificação de erros de preenchimento

---

## 6️⃣ Verificação de Pontuação em Textos (NLP)

### 📖 Descrição

Neste exercício foi desenvolvido um sistema simples de validação textual voltado para Processamento de Linguagem Natural.

O programa verifica se as palavras de uma lista ainda contêm símbolos de pontuação que deveriam ter sido removidos.

### 🎯 Conceitos trabalhados

* NLP
* Validação textual
* Estruturas condicionais
* `ValueError`
* Processamento de strings

### ✅ Funcionalidades

* Identificação de pontuações
* Validação de limpeza textual
* Detecção do primeiro erro encontrado
* Tratamento de inconsistências

---

## 7️⃣ Divisão de Colunas em Experimentos Científicos

### 📖 Descrição

Este programa foi desenvolvido para auxiliar um laboratório no processamento de dados experimentais.

O sistema calcula a razão entre pressão e temperatura em ambientes controlados.

Também são realizadas verificações de consistência para garantir que os dados sejam válidos.

### 🎯 Conceitos trabalhados

* Funções
* Manipulação de listas
* `zip()`
* `ValueError`
* `ZeroDivisionError`
* Processamento de dados científicos

### ✅ Funcionalidades

* Divisão de colunas numéricas
* Validação do tamanho das listas
* Verificação de divisão por zero
* Geração de nova coluna calculada

---

# 🛠️ Tecnologias Utilizadas

* Python 3
* Tratamento de exceções
* Estruturas condicionais
* Estruturas de repetição
* List comprehension
* Manipulação de listas
* Manipulação de dicionários
* Manipulação de strings
* Programação funcional

---

# 🎓 Aprendizados Desenvolvidos

Durante o desenvolvimento destes exercícios foram praticadas habilidades essenciais para programação e análise de dados:

* Escrita de código mais seguro
* Tratamento de erros em aplicações
* Validação de entradas de usuários
* Processamento de informações textuais
* Estruturação de funções reutilizáveis
* Manipulação de coleções em Python
* Organização lógica de dados
* Desenvolvimento de sistemas mais robustos

---

# 📌 Aplicações Reais

Os conceitos aplicados nestes exercícios são amplamente utilizados em:

* Ciência de Dados
* Engenharia de Dados
* Desenvolvimento Backend
* Automação de Processos
* Processamento de Linguagem Natural (NLP)
* Sistemas de Correção Automática
* Validação de Dados
* Sistemas Científicos e Laboratoriais

---

# 📚 Estruturas e Recursos Utilizados

Os exercícios utilizam recursos importantes da linguagem Python:

| Recurso              | Aplicação                      |
| -------------------- | ------------------------------ |
| `try-except`         | Tratamento de exceções         |
| `finally`            | Finalização segura de execução |
| `zip()`              | Pareamento de listas           |
| `raise`              | Lançamento manual de exceções  |
| `list comprehension` | Criação otimizada de listas    |
| Dicionários          | Estruturação de dados          |
| Funções              | Reutilização de código         |

---

# 📌 Conclusão

Os exercícios deste repositório demonstram aplicações práticas de tratamento de exceções e validação de dados em Python.

Além de fortalecer conceitos fundamentais da linguagem, os programas mostram como desenvolver aplicações mais seguras, organizadas e preparadas para lidar com erros em cenários reais.

Essas habilidades são extremamente importantes em áreas como desenvolvimento de software, automação, ciência de dados e inteligência artificial.

---

Projeto desenvolvido para fins de estudo, prática em Python e fortalecimento do pensamento computacional aplicado à análise de dados. Como parte de aulas práticas da trilha de Especialista em IA da Alura
