Desafio Sistema Bancario Versão 3

Este desafio faz parte da atividade do Bootcamp - Suzano - Python Developer que estou realizando na plataforma da DIO (Digital Innovation One) , em parceria com a empresa SUZANO .
Este projeto é uma implementação de um sistema bancário simples utilizando Programação Orientada a Objetos (POO) em Python. O sistema permite a criação de clientes, contas bancárias, e a realização de operações básicas como depósito, saque e consulta de extrato.

Objetivo Geral
O objetivo principal deste projeto é modelar um sistema bancário utilizando conceitos, como classes, herança, encapsulamento e métodos abstratos. O sistema armazena os dados de clientes e contas bancárias em objetos, ao invés de dicionários, seguindo um modelo de classes UML.

Funcionalidades
Criação de Clientes : Os clientes podem ser cadastrados no sistema com informações como nome, data de nascimento, CPF e endereço.
Criação de Contas Bancárias : Cada cliente pode ter uma ou mais contas bancárias, com funcionalidades de depósito, saque e consulta de extrato.
Operações Bancárias :
Depósito : Permite ao cliente depositar dinheiro em sua conta.
Saque : Permite ao cliente sacar dinheiro de sua conta, respeitando os limites diários e de saldo.
Extrato : Exibe o histórico de transações e o saldo atual da conta.
Modelagem das Classes
O sistema é composto pelas seguintes classes:

Cliente : Representa um cliente do banco, com atributos como nome, CPF, data de nascimento e endereço.
PessoaFisica : Herda de Clientee representa um cliente pessoa física.
Conta : Representa uma conta bancária, com atributos como número da conta, agência, saldo e histórico de transações.
ContaCorrente : Herda de Contae implementa funcionalidades específicas de uma conta corrente, como limite de saque e número máximo de saques diários.
Histórico : Armazena o histórico de transações de uma conta.
Transacao : Classe abstrata que define uma interface para transações bancárias.
Saque e Deposito : Classes que herdam de Transacaoe implementam as operações de saque e depósito, respectivamente.
