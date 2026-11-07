# Sistema Bancário – Etapa 2

**Aluno:** Andre Flavio Corcini de Abreu  
**Instituição:** Centro Universitário de Viçosa – UNIVIÇOSA  
**Disciplina:** INF101 – Programação de Computadores I  
**Linguagem:** C++

## 1. Descrição do Projeto

Este projeto consiste no desenvolvimento de um Sistema de Registro e Gestão de Contas Bancárias, utilizando a linguagem C++.

O sistema permite cadastrar e gerenciar várias contas bancárias, realizar operações financeiras e consultar o histórico de movimentações.

Os dados são armazenados em memória utilizando arrays.

## 2. Funcionalidades

O programa possui as seguintes funcionalidades:

1. Cadastrar contas bancárias.
2. Listar contas cadastradas.
3. Consultar uma conta pelo número.
4. Realizar depósitos.
5. Realizar saques com verificação de saldo.
6. Realizar transferências entre contas.
7. Exibir extrato bancário.
8. Encerrar o sistema.

## 3. Tecnologias Utilizadas

- Linguagem C++.
- Biblioteca iostream.
- Biblioteca string.
- Biblioteca iomanip.
- Arrays.
- Estruturas condicionais (if, else e switch).
- Estruturas de repetição (for e do while).

## 4. Armazenamento dos Dados

O sistema utiliza arrays para armazenar as informações:

- Número da conta.
- Nome do cliente.
- CPF.
- Tipo de conta.
- Saldo.
- Situação da conta.

Também utiliza arrays para registrar as movimentações bancárias:

- Número da conta.
- Tipo de movimentação.
- Valor movimentado.

**Limites do sistema:**
- Até 100 contas bancárias.
- Até 500 movimentações.

## 5. Regras de Funcionamento

- Não permite cadastrar números de contas repetidos.
- Não permite depósitos com valores negativos ou iguais a zero.
- Não permite saques com saldo insuficiente.
- Não permite transferências para a mesma conta.
- Verifica se as contas existem antes de realizar transferências.
- Registra depósitos, saques e transferências no histórico.

## 6. Como Executar o Programa

1. Abra o Code::Blocks ou outro compilador C++.
2. Crie um arquivo chamado `main.cpp`.
3. Copie o código-fonte do projeto.
4. Compile o programa.
5. Execute e utilize o menu apresentado na tela.

## 7. Limitações

Nesta etapa, os dados são armazenados somente na memória do computador.

Ao fechar o programa, as contas cadastradas e as movimentações são perdidas.

A gravação permanente dos dados será implementada em uma próxima etapa.

## 8. Objetivo do Trabalho

O objetivo é aplicar os conhecimentos de programação em C++, utilizando arrays, estruturas de decisão e repetição para desenvolver um sistema bancário simples e funcional.

---

**Trabalho desenvolvido para a disciplina INF101 – Programação de Computadores I.**
