# Code_Bank
**Sistema de Gerenciamento de Contas**

Este é um programa simples para gerenciar contas bancárias. Ele permite ao usuário criar uma conta, depositar e sacar dinheiro e verificar o saldo atual.

**Uso**

Para usar o programa, siga as instruções exibidas na tela. O usuário precisa inserir o número da conta, o nome do titular da conta e se há ou não um depósito inicial. Se houver um depósito inicial, o usuário precisa inserir o valor do depósito.

Uma vez que a conta é criada, o usuário pode fazer um depósito ou um saque. Após cada transação, o programa exibirá os dados atualizados da conta, incluindo o saldo atual.

**Implementação**

O programa é implementado em Java, usando a classe Account para representar uma conta bancária. A classe tem os seguintes atributos:

número: um inteiro representando o número da conta
nome: uma string representando o nome do titular da conta
saldo: um double representando o saldo da conta
A classe Account tem os seguintes métodos:

deposit (double amount): adiciona a quantidade dada ao saldo da conta
withdraw(double amount): subtrai a quantidade dada do saldo da conta, mais uma taxa de 5,0
toString (): retorna uma representação de string dos dados da conta
O programa usa um objeto Scanner para ler a entrada do usuário e um objeto Locale para definir o local padrão como US, para que o separador decimal seja um ponto.

**Melhorias futuras**

Adicionar tratamento de erros para entradas inválidas

Implementar um sistema de menu para facilitar a interação do usuário com o programa

Armazenar dados da conta em um banco de dados para torná-los persistentes entre as execuções do programa

-------------------
**Account Management System**
This is a simple program to manage bank accounts. It allows the user to create an account, deposit and withdraw money, and check the current balance.

**Usage**

To use the program, follow the instructions displayed on the screen. The user needs to input the account number, the account holder's name, and whether there is an initial deposit or not. If there is an initial deposit, the user needs to input the value of the deposit.

Once the account is created, the user can make a deposit or a withdrawal. After each transaction, the program will display the updated account data, including the current balance.

**Implementation**

The program is implemented in Java, using the Account class to represent a bank account. The class has the following attributes:

number: an integer representing the account number
name: a string representing the account holder's name
balance: a double representing the account balance
The Account class has the following methods:

deposit(double amount): adds the given amount to the account balance
withdraw(double amount): subtracts the given amount from the account balance, plus a fee of 5.0
toString(): returns a string representation of the account data
The program uses a Scanner object to read input from the user and a Locale object to set the default locale to US, so that the decimal separator is a dot.

**Future improvements**

Add error handling for invalid inputs
Implement a menu system to make it easier for the user to interact with the program
Store account data in a database to make it persistent between program runs
