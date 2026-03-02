# Sistema Bancário - SeuDinheiroEMeuGYN

Modelagem de um sistema bancário central para substituir a gestão precária feita por planilhas, focando em segurança e integridade referencial.

## 🎯 Objetivo
Implementar um relacionamento um-para-um (1:1) entre Clientes e Contas Bancárias, garantindo que cada cliente tenha apenas uma conta e cada conta pertença a apenas um cliente.

## 🛠️ Tecnologias e Conceitos
* **Relacionamento 1:1:** Uso de `FOREIGN KEY` combinada com `UNIQUE` no campo `cpf` da tabela de contas.
* **Histórias de Usuário:** Tradução de requisitos de negócio em restrições técnicas (ex: limite de crédito apenas para contas 'Especial').
* **Modularidade:** Divisão do sistema em tabelas `Cliente` e `contaBancaria` para melhor organização.

## 🚀 Como Executar
1. O script oferece três opções de implementação (Tabela única, FK na conta ou FK no cliente).
2. A **Opção 2** é a recomendada para este modelo de negócio.
3. Execute primeiro a criação da tabela `Cliente` e depois `contaBancaria` para respeitar as dependências de chave.
