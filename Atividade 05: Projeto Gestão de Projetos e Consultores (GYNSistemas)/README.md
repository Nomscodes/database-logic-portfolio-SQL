# GYNSistemas - Gestão de Projetos e Consultores 💼

## 📌 Descrição
O **GYNSistemas** é um sistema de banco de dados projetado para o gerenciamento de consultores e seus respectivos projetos vinculados. O projeto aborda a complexidade de manter registros detalhados de profissionais, incluindo dados de contato e localização, associados a projetos com controle de custos e prazos.

## 🛠️ Etapas do Projeto
* **Modelo Conceitual (MER):** Define as entidades `Consultor` e `Projeto`, destacando o relacionamento `r1` entre elas.
* **Dicionário de Dados:** Documentação técnica contendo a descrição, tipo, formato e restrições de cada atributo.
* **Modelo Lógico:** Análise de três opções de estruturação, com a escolha da **Opção 2** como a melhor solução (Tabela `Projeto` referenciando `Consultor` via CPF).
* **Modelo Físico:** Scripts DDL para criação das tabelas com implementação de `PRIMARY KEY`, `FOREIGN KEY` e restrições de unicidade (`UNIQUE`).

## 🔍 Destaque Técnico: Atributos Compostos
Um diferencial deste projeto é a desconstrução de atributos compostos do MER (como Endereço e Telefone) em colunas específicas no modelo físico (Logradouro, CEP, DDI, DDD, etc.), garantindo maior granularidade e facilidade de busca nos dados.

## 📂 Conteúdo sugerido do Repositório
* `MER_GYNSistemas.jpg`: Modelo conceitual das entidades.
* `Dicionario_Atributos.pdf`: Regras de negócio e domínios.
* `Database_Schema.sql`: Script de implementação física (SQL).

---
Desenvolvido por **Cassiano Nunes de Abreu**.
