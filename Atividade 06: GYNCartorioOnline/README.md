# GYNCartorioOnline 📜

## 📌 Descrição
O **GYNCartorioOnline** é um projeto de banco de dados desenvolvido para gerenciar o registro de cidadãos e suas respectivas uniões estáveis. O foco principal foi a correta estruturação das informações civis, garantindo a integridade dos dados através de diferentes abordagens de modelagem (Lógica e Física).

## 🛠️ Etapas do Projeto
O repositório contém a documentação completa do ciclo de vida do banco de dados:
* **Modelo Conceitual (MER):** Focado na entidade `Cidadao` e no relacionamento de `uniao`.
* **Dicionário de Dados:** Definição detalhada de tipos, tamanhos e restrições de cada atributo.
* **Modelo Lógico:** Comparativo entre três opções de normalização, destacando a separação das tabelas `Cidadao` e `uniaoEstavel` como a melhor solução (Opção 3).
* **Modelo Físico:** Scripts SQL de criação de tabelas (`CREATE TABLE`) com definições de chaves primárias e estrangeiras.

## 🔍 Destaque Técnico: Normalização
A solução escolhida separa a entidade de união para evitar redundância de dados, utilizando uma `Foreign Key` para vincular o companheiro ao cadastro do cidadão. Isso permite que as informações de registro e data da união sejam armazenadas de forma independente e organizada.

## 📂 Estrutura sugerida de Arquivos
* `modelagem_conceitual.png`: Diagrama do MER.
* `dicionario_dados.pdf`: Detalhamento dos atributos.
* `script_criacao.sql`: Comandos DDL para o banco de dados.

---
Desenvolvido por **Cassiano Nunes de Abreu**.
