# Gestão da Temporada 2026 - Fórmula 1

Desenvolvimento de um banco de dados para a Liberty Media focado no controle de pilotos, equipes, motores e pontuações da temporada de 2026.

## 🎯 Objetivo
Garantir o armazenamento seguro e estruturado dos dados da competição, permitindo atualizações constantes conforme o decorrer da temporada.

## 🛠️ Tecnologias e Conceitos
* **DML Avançado:** Prática intensiva de manipulação de dados.
    * **INSERT:** Carga de dados reais de pilotos como Adrian Sutil e Carlos Sainz Jr.
    * **UPDATE:** Atualização de nomes e pontuações utilizando a matrícula como filtro.
    * **DELETE:** Remoção controlada de registros da base[cite: 521].
* **Tipagem:** Uso de `INT` para pontuação e idade, e `VARCHAR` para nomes e equipes.

## 🚀 Como Executar
1. Execute a criação da tabela `Piloto`.
2. Popule a tabela com o bloco de `INSERT` fornecido.
3. Teste as atualizações e deleções para entender o comportamento da cláusula `WHERE`.
