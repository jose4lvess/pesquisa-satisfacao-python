# 📊 Pesquisa de Satisfação - TudoWeb

## 📝 Descrição

Este projeto consiste em um programa desenvolvido em Python para realizar uma pesquisa de satisfação com clientes da empresa **TudoWeb**.

O sistema coleta informações dos entrevistados e analisa o nível de satisfação em relação ao atendimento prestado.

---

## 🎯 Objetivo

Desenvolver um algoritmo utilizando:

* Estrutura de repetição `for`
* Estruturas de decisão (`if`, `elif`, `else`)
* Entrada e saída de dados

---

## ⚙️ Funcionalidades

* Coleta de dados de até 50 entrevistados:

  * Nome
  * Idade
  * Opinião sobre o atendimento
* Classificação das respostas:

  * 1 → Excelente
  * 2 → Bom
  * 3 → Ruim
* Exibição do resultado final com:

  * Total de respostas **EXCELENTE**
  * Total de respostas **RUIM**

---

## 🧠 Lógica Utilizada

O programa utiliza um laço de repetição `for` para executar a coleta de dados de forma contínua.

As respostas são analisadas com estruturas condicionais:

* Se a resposta for 1 → incrementa o contador de excelente
* Se a resposta for 3 → incrementa o contador de ruim

---

## 💻 Tecnologias Utilizadas

* Python 
* Visual Studio Code
---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```
https://github.com/jose4lvess?tab=repositories
```

2. Acesse a pastaa:

```
pesquisa-satisfacao-python
```

3. Execute o programa:

```
pesquisa.py
```

---

## 🧪 Testes

Para facilitar os testes, o programa pode ser executado com apenas 10 entrevistados, alterando o intervalo do `for`:

```python
for i in range(1, 11):
```

Após a validação, o valor deve ser ajustado novamente para 50 entrevistados.

---

## 📌 Exemplo de Saída

```
=== RESULTADO DA PESQUISA ===
Quantidade de EXCELENTE: 20
Quantidade de RUIM: 10
```

---

## 👨‍💻 Autor

Projeto desenvolvido por **José Alves** como atividade acadêmica.

---

## 📚 Competências Desenvolvidas

* Lógica de programação
* Estruturas de repetição
* Estruturas condicionais
* Organização de código
