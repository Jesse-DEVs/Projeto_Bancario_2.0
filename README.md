🏦 Sistema Bancário_ 2.0 em Python

Este projeto é um sistema bancário simples, criado com foco no aprendizado de Programação Orientada a Objetos (POO) com Python. Ele simula operações básicas de um banco, como criação de contas, cadastro de clientes, depósitos, saques e geração de extratos.

🚀 Funcionalidades
Cadastro de clientes (Pessoa Física);

Criação de contas-correntes com limite de saque;

Depósitos e saques com histórico de transações;

Geração de extratos;

Controle de número de saques permitidos;

Iterador personalizado para listagem de contas;

Aplicação de princípios da POO como:

Herança;

Abstração com ABC;

Propriedades;

Métodos de classe e decoradores personalizados;

Encapsulamento.

🧱 Estrutura de Classes
Cliente e PessoaFisica: Representam os clientes do banco.

Conta e ContaCorrente: Gerenciam os dados bancários e transações.

Transacao, Saque e Deposito: Usadas para registrar movimentações na conta.

Historico: Armazena todas as transações realizadas por uma conta.

ContasIterador: Permite iterar e visualizar as contas cadastradas.

📜 Exemplo de uso
No menu interativo, é possível:

[1] Depositar 

[2] Sacar 

[3] Extrato 

[4] Nova conta 

[5] Listar contas  

[6] Novo usuário 

[0] Sair 

⚙️ Tecnologias Utilizadas
Python 3.x

Módulos padrão: datetime, textwrap, abc

📝 Melhorias futuras
Limite diário de transações;

Validação mais robusta de dados (CPF, datas, etc.);

Interface gráfica (GUI) com Tkinter ou web com Flask/Django;

Integração com banco de dados para persistência de dados.

