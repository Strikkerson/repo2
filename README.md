# Banco de Dados LAN House

## Tabela Cliente

| Nome do Campo  | Tipo         |
| -------------  | ------------ |
| IDcliente (PK) | INT          |
| nome           | VARCHAR(100) |
| idade          | INT          |
| telefone       | VARCHAR(30)  |
| email          | VARCHAR(50)  |
| saldo_horas    | INT          |

## Tabela Funcionario

| Nome do Campo      | Tipo         |
| ------------------ | ------------ |
| IDfuncionario (PK) | INT          |
| nome               | VARCHAR(100) |
| idade              | INT          |
| cpf                | VARCHAR(30)  |
| telefone           | VARCHAR(30)  |
| email              | VARCHAR(50)  |
| cargo              | INT          |
| salario            | DOUBLE       |

## Tabela Computadores

| Nome do Campo    | Tipo         |
| -------------    | ------------ |
| IDpc (PK)        | INT          |
| processador      | VARCHAR(100) |
| gpu              | VARCHAR(30)  |
| ram              | VARCHAR(50)  |
| data_manuntencao | DATE         |
