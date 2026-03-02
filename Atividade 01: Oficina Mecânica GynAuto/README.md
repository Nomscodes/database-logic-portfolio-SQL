# Oficina Mecânica GynAuto - Gestão de Clientes

Este projeto faz parte da modernização da oficina GynAuto, substituindo o controle manual por um banco de dados relacional estruturado.

## 🎯 Objetivo
Desenvolver uma base de dados robusta para o armazenamento seguro e organizado das informações dos clientes, facilitando a recuperação de dados e evitando inconsistências.

## 🛠️ Tecnologias e Conceitos
* **SQL (PostgreSQL/MySQL):** Implementação do modelo físico.
* **Entidade Única:** Foco na modelagem da tabela `cliente`.
* **Integridade de Dados:** * Uso de `PRIMARY KEY` no CPF.
    * Atributos `NOT NULL` para campos obrigatórios.
    * Cláusulas `UNIQUE` para e-mails e telefones.

## 🚀 Como Executar
1. Execute o script de criação da tabela `cliente`.
2. Utilize o comando `INSERT` para popular a base.
3. Realize consultas utilizando `SELECT * FROM cliente`.
