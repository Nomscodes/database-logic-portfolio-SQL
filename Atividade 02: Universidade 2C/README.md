# Sistema Acadêmico - Universidade 2C

O projeto visa otimizar a gestão de dados dos professores da Universidade 2C, permitindo consultas rápidas e precisas sobre o corpo docente.

## 🎯 Objetivo
Criar um esquema relacional que suporte informações detalhadas como graus acadêmicos, tipos de contrato, múltiplos endereços e documentos (CPF, RG, CTPS).

## 🛠️ Tecnologias e Conceitos
* **Domínios Customizados:** Implementação de `CREATE TYPE ... AS ENUM` para `TTitulacao` e `TTipoContrato`.
* **Constraints de Verificação:** Uso de `CHECK` para validar o campo `sexo`.
* **Normalização:** Estruturação de campos para múltiplos e-mails, telefones e endereços.
* **Segurança de Dados:** Atributos `UNIQUE` aplicados ao CPF e e-mails para evitar duplicidade.

## 🚀 Como Executar
1. Crie os tipos enumerados antes da tabela.
2. Execute o script `create table professor`.
3. O script inclui validações para garantir que informações obrigatórias, como matrícula e nome, sejam preenchidas.
