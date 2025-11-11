💳 Sistema Bancário em Python 💻

Este é um projeto de estudo de um sistema bancário simples desenvolvido em Python. O foco do projeto é aprender e aplicar conceitos de Programação Orientada a Objetos (POO), como herança, polimorfismo, e abstração, modelando um ambiente bancário fictício.

🚀 Funcionalidades

O sistema permite a criação de clientes e contas bancárias, além de permitir a realização de operações como depósitos, saques e consultas de extrato. As funcionalidades disponíveis são:

Cadastro de novos clientes: Criação de um cliente com nome, CPF, data de nascimento e endereço. 📑

Criação de contas bancárias: Para cada cliente, é possível criar uma conta corrente. 💰

Operações bancárias:

Depósito: Realize depósitos em uma conta bancária. 💵

Saque: Realize saques dentro de limites e restrições. 💸

Extrato: Visualize o histórico de transações e o saldo disponível. 📃

Limites de saques: O sistema permite configurar um limite para saques diários e um número máximo de saques por dia. ⏳

🏗️ Estrutura do Projeto

O projeto é composto pelas seguintes classes principais:

Cliente: Representa um cliente, que pode ter várias contas bancárias. 👤

PessoaFisica: Herda de Cliente, representando um cliente do tipo pessoa física. 🧑‍🤝‍🧑

Conta: Representa uma conta bancária genérica com operações básicas de depósito e saque. 🏦

ContaCorrente: Herda de Conta e adiciona limites específicos para saques. 💳

Transacao: Classe abstrata que define os métodos para as transações. 🔄

Saque e Deposito: Implementações de transações específicas para saque e depósito. 💵💳

🛠️ Como Rodar o Projeto
🔧 Pré-requisitos

Certifique-se de que você tem o Python 3.x instalado na sua máquina. Caso não tenha, faça o download e instale a versão mais recente do Python aqui
.

🚀 Executando o Sistema

Clone o repositório para sua máquina local:

git clone https://github.com/SEU-USUARIO/nome-do-repositorio.git
cd nome-do-repositorio


Execute o arquivo principal main.py:

python main.py

🖥️ Fluxo de Execução

Ao rodar o programa, você verá um menu interativo no terminal com as seguintes opções:

=============== MENU ================
[d]    Depositar
[s]    Sacar
[e]    Extrato
[nc]   Nova conta
[lc]   Listar contas
[nu]   Novo usuário
[q]    Sair
=> 


Escolha a operação desejada digitando a letra correspondente. O sistema solicitará informações, como CPF do cliente, valor da transação e exibirá mensagens de confirmação ou erro.

💡 Exemplo de Execução

Ao executar o programa, o terminal pode exibir algo como:

=============== MENU ================
[d]    Depositar
[s]    Sacar
[e]    Extrato
[nc]   Nova conta
[lc]   Listar contas
[nu]   Novo usuário
[q]    Sair
=> 


Dependendo da escolha, o programa solicitará detalhes como CPF do cliente, valor do depósito ou saque, e exibirá o extrato com as transações realizadas.
