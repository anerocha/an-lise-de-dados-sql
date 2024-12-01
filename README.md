# Exploração e Análise de Dados com SQL

Este projeto faz parte de um curso de análise de dados focado em explorar e analisar dados de clientes de um banco usando SQL. O objetivo é investigar diversos aspectos do comportamento dos clientes, incluindo salário, limite de crédito, histórico de transações e mais, por meio de consultas SQL estruturadas.

---

## Visão Geral do Projeto

O conjunto de dados inclui informações sobre os clientes, como:

- **idade**: Idade do cliente
- **sexo**: Sexo do cliente (F ou M)
- **dependentes**: Número de dependentes do cliente
- **escolaridade**: Nível de escolaridade do cliente
- **salario_anual**: Faixa salarial do cliente
- **tipo_cartao**: Tipo de cartão de crédito (por exemplo, Gold, Platinum)
- **qtd_produtos**: Quantidade de produtos comprados nos últimos 12 meses
- **iteracoes_12m**: Número de transações realizadas nos últimos 12 meses
- **meses_inativo_12m**: Número de meses que o cliente esteve inativo nos últimos 12 meses
- **limite_credito**: Limite de crédito do cliente
- **valor_transacoes_12m**: Valor total das transações nos últimos 12 meses
- **qtd_transacoes_12m**: Número de transações realizadas nos últimos 12 meses

O objetivo deste projeto é explorar esses dados e obter insights significativos que possam ajudar uma empresa a entender melhor seu público.

---

## Estrutura do Projeto

O repositório inclui consultas SQL para explorar e analisar o conjunto de dados de maneira estruturada. As seguintes seções representam diferentes áreas de exploração e análise:

### 1. **Consultas de Exploração:**
   - Contar o número de registros no conjunto de dados.
   - Exibir as primeiras 10 linhas para entender a estrutura dos dados.
   - Descrever os tipos de dados de cada coluna da tabela.
   - Verificar valores distintos nas colunas como `escolaridade`, `estado_civil`, `salario_anual` e `tipo_cartao`.

### 2. **Consultas de Análise:**
   - Analisar a distribuição de clientes por faixas salariais e sexo.
   - Investigar a relação entre salário e limite de crédito.
   - Comparar o valor das transações entre clientes homens e mulheres.
   - Analisar clientes com os maiores e menores limites de crédito.
