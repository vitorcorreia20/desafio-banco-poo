# 🏦 Desafio Banco Digital com POO

![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![POO](https://img.shields.io/badge/Orientação_a_Objetos-black?style=for-the-badge)

## 🎯 Sobre o Projeto

Este repositório contém a minha solução para o desafio **"Criando um Banco Digital com Java e Orientação a Objetos"**, proposto frequentemente em bootcamps de tecnologia. 

A proposta do projeto é simular o funcionamento básico de um banco, modelando o domínio da aplicação e implementando as regras de negócio de diferentes tipos de contas bancárias, tudo isso utilizando os pilares da Programação Orientada a Objetos (POO).

## ⚙️ Funcionalidades Implementadas

O sistema bancário simulado permite as seguintes operações básicas:

* **Criação de Clientes e Contas:** Associação de um cliente a uma conta bancária.
* **Tipos de Contas:** Diferenciação entre Conta Corrente e Conta Poupança.
* **Depósitos e Saques:** Validação de saldo para retirar e adicionar valores.
* **Transferências:** Envio de valores de uma conta para outra com atualização instantânea dos saldos.
* **Extrato Bancário:** Impressão dos dados da conta e saldo atual.

## 🧠 Arquitetura e Conceitos (POO)

A estrutura do projeto foi desenhada para aplicar os quatro pilares fundamentais da Orientação a Objetos:

* **Abstração:** Criação de uma classe mãe/interface `Conta` que define o contrato básico de qualquer conta bancária.
* **Encapsulamento:** Os saldos e dados sensíveis dos clientes são privados e só podem ser manipulados através de métodos específicos.
* **Herança:** As classes `ContaCorrente` e `ContaPoupanca` herdam atributos e comportamentos genéricos da classe mãe `Conta`.
* **Polimorfismo:** Possibilidade de tratar diferentes tipos de contas de forma genérica na hora de imprimir extratos ou realizar operações.

## 🛠️ Tecnologias Utilizadas

* **[Linguagem]** Java
* Paradigma de Programação Orientada a Objetos (POO)
