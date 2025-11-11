# 💳 Sistema Bancário em Python 💻

Este é um **projeto de estudo** de um **sistema bancário simples** desenvolvido em Python. O foco do projeto é aprender e aplicar conceitos de **Programação Orientada a Objetos (POO)**, como herança, polimorfismo, e abstração, modelando um ambiente bancário fictício.

## 🚀 Funcionalidades

O sistema permite a criação de clientes e contas bancárias, além de permitir a realização de operações como **depósitos**, **saques** e **consultas de extrato**. As funcionalidades disponíveis são:

- **Cadastro de novos clientes**: Criação de um cliente com nome, CPF, data de nascimento e endereço. 📑
- **Criação de contas bancárias**: Para cada cliente, é possível criar uma **conta corrente**. 💰
- **Operações bancárias**:
  - **Depósito**: Realize depósitos em uma conta bancária. 💵
  - **Saque**: Realize saques dentro de limites e restrições. 💸
  - **Extrato**: Visualize o histórico de transações e o saldo disponível. 📃
- **Limites de saques**: O sistema permite configurar um limite para saques diários e um número máximo de saques por dia. ⏳

## 🏗️ Estrutura do Projeto

O projeto é composto pelas seguintes classes principais:

- **Cliente**: Representa um cliente, que pode ter várias contas bancárias. 👤
- **PessoaFisica**: Herda de `Cliente`, representando um cliente do tipo pessoa física. 🧑‍🤝‍🧑
- **Conta**: Representa uma conta bancária genérica com operações básicas de depósito e saque. 🏦
- **ContaCorrente**: Herda de `Conta` e adiciona limites específicos para saques. 💳
- **Transacao**: Classe abstrata que define os métodos para as transações. 🔄
- **Saque** e **Deposito**: Implementações de transações específicas para saque e depósito. 💵💳


