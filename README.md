# ☕ Análise de Vendas de Café

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

**Análise de dados de vendas de um café, com foco em limpeza de dados e insights estratégicos.**  
Este projeto explora um dataset de 10,000 transações, realizando limpeza de dados e respondendo perguntas de negócio.

---

## 📌 Visão Geral

### Contexto
O dataset contém transações de vendas de um café, com dados inconsistentes:
- Valores ausentes (`None`, `UNKNOWN`).
- Erros de entrada (`ERROR`, valores não numéricos).
- Inconsistências entre colunas (ex.: `Total Spent` ≠ `Quantity * Price Per Unit`).

### Objetivo
Transformar dados "sujos" em insights acionáveis, como:
- Identificar padrões de vendas e preferências de clientes.
- Otimizar estoque e escalonamento de funcionários.

### 📊 Análise e Resultados
1. Limpeza de Dados
Valores ausentes: Remoção de registros com Item ou Price Per Unit ausentes.

Correção de preços: Padronização usando um dicionário de preços fixos.

Datas inválidas: Remoção de registros com datas fora do padrão.

Padronização: Unificação de categorias (ex.: In-store vs. In store).

2. Análise Exploratória
Item mais vendido: Salad, Sandwich e Smoothie.

Método de pagamento: Digital Wallet é o mais popular.


