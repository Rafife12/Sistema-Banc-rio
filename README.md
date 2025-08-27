# 🏦 Sistema Bancário Simples em Python

Este projeto implementa um sistema bancário básico em Python, permitindo realizar depósitos, saques e consultar o extrato.  
Foi desenvolvido com o objetivo de praticar lógica de programação, estruturas de repetição e condicionais.

---

## 🚀 Funcionalidades

- **Depósito (`d`)**  
  Permite adicionar um valor positivo ao saldo da conta.  
  - Apenas valores maiores que zero são aceitos.

- **Saque (`s`)**  
  Permite retirar dinheiro da conta, respeitando as seguintes regras:  
  - Limite máximo de **R$ 500,00 por saque**.  
  - Máximo de **3 saques por dia**.  
  - O valor não pode ser maior que o saldo disponível.  

- **Extrato (`e`)**  
  Mostra todas as movimentações realizadas (depósitos e saques) e o saldo atual.  
  Caso não haja movimentações, exibe uma mensagem informando.

- **Sair (`q`)**  
  Encerra o programa.

---

## 📋 Regras do Sistema

- O saldo inicial é **R$ 0,00**.  
- Limite de saque: **R$ 500,00 por operação**.  
- Limite de operações de saque: **3 por dia**.  
- Valores inválidos (≤ 0) não são aceitos.

---

## 🖥️ Exemplo de Uso

[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair

=> d
Informe o valor do depósito: 200

=> s
Informe o valor do saque: 50

=> e

================ EXTRATO ================
Depósito: R$ 200.00
Saque: R$ 50.00

Saldo: R$ 150.00


---

## 📚 Conceitos Aplicados

- Estruturas condicionais (`if/elif/else`)  
- Estruturas de repetição (`while`)  
- Controle de fluxo com `break`  
- Manipulação de strings (concatenação para extrato)  
- Boas práticas de programação (validação de entrada)

---

## 🛠️ Como Executar

1. Clone este repositório ou copie o código para um arquivo `sistema_bancario.py`.
2. Execute o programa em seu terminal:

```bash
python sistema_bancario.py
