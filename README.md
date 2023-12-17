# Sistema-Bancario-JDBC-JAVA

Sistema desenvolvido em Java realizando um CRUD num banco de dados mysql, simulando uma operação bancária.

Banco de dados necessário para rodar:

Nome: byte_bank;

CREATE DATABASE byte_bank;

mysql> CREATE TABLE `conta` (
    ->   `numero` int NOT NULL,
    ->   `saldo` decimal(10,0) DEFAULT NULL,
    ->   `cliente_nome` varchar(50) DEFAULT NULL,
    ->   `cliente_cpf` varchar(11) DEFAULT NULL,
    ->   `cliente_email` varchar(50) DEFAULT NULL,
    ->    PRIMARY KEY (`numero`),
    ->    esta_ativa boolean default true
    -> ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

