# 📊 Projeto de Análise de Vendas - Pipeline Completo com Excel

## 📌 Sobre o Projeto

Este projeto apresenta o desenvolvimento completo de uma solução de análise de dados de vendas, desde a geração e tratamento da base até a construção de um dashboard interativo.

O objetivo foi simular um cenário real de negócio, aplicando boas práticas de análise de dados, organização e visualização.

---

## 🎯 Objetivo

Construir uma solução analítica que permita:

* Entender o desempenho de vendas
* Comparar resultados com metas
* Identificar padrões e oportunidades
* Apoiar a tomada de decisão com dados

---

## 🧱 Estrutura do Projeto

O projeto foi dividido em 4 etapas principais:

---

### 🔹 1. Geração da Base de Dados

* Base simulada com 500 registros
* Dados gerados via script em Python
* Inclusão intencional de inconsistências para simular cenário real:

  * Valores nulos
  * Valores negativos
  * Dados inconsistentes

---

### 🔹 2. Tratamento de Dados (Power Query)

* Remoção de valores nulos e inválidos
* Exclusão de registros com erros (ex: valores negativos)
* Padronização de tipos:

  * Moeda (R$)
  * Percentual (%)
* Criação de colunas auxiliares:

  * Ano
  * Mês
* Ajuste de inconsistências na coluna de ID

---

### 🔹 3. Modelagem e KPIs (Tabelas Dinâmicas)

Criação de indicadores estratégicos a partir de tabelas dinâmicas:

* 💰 Total de Vendas
* 🎯 Meta Total
* 📊 Percentual de Atingimento
* 💸 Premiação Total

Todos os KPIs foram estruturados para responder dinamicamente aos filtros aplicados.

---

### 🔹 4. Dashboard Interativo

Construção de uma interface visual com foco em clareza e tomada de decisão:

#### 🔝 Indicadores Principais (Cards)

* Total de Vendas
* Meta Total
* Percentual de Atingimento

#### 📈 Análises Visuais

* 🏆 Vendas por Vendedor (ranking)
* 📢 Vendas por Campanha
* 💸 Premiação por Vendedor
* 📍 Vendas por Região

#### 🎛️ Filtros Interativos

* Ano
* Mês
* Região

Todos os elementos são dinâmicos e conectados às tabelas dinâmicas.

---

## 🛠️ Tecnologias Utilizadas

* Python (geração de dados)
* Microsoft Excel
* Power Query
* Tabelas Dinâmicas
* Segmentação de Dados

---

## ⚙️ Funcionalidades

* Tratamento de dados automatizado
* Dashboard interativo
* Atualização dinâmica via filtros
* Separação entre camada de dados e visualização

---

## 🚀 Como Executar

1. Executar o script Python para gerar a base de dados (opcional)
2. Abrir o arquivo Excel
3. Atualizar consultas no Power Query (se necessário)
4. Navegar até a aba **Dashboard**
5. Utilizar os filtros para análise

---

## 💡 Diferenciais do Projeto

* Simulação de cenário real com dados imperfeitos
* Pipeline completo de dados (end-to-end)
* Uso de boas práticas de organização
* Foco em análise e tomada de decisão
* Estrutura semelhante a projetos corporativos

---

## 📎 Possíveis Melhorias Futuras

* Integração com banco de dados (SQL)
* Automatização da ingestão de dados
* Migração para Power BI
* Inclusão de novos KPIs (ticket médio, crescimento, churn)

---

## 👨‍💻 Autor

* Felipe Passos de Albuquerque
* Estudante de Ciência da Computação
* Foco em Análise e Ciência de Dados

---
