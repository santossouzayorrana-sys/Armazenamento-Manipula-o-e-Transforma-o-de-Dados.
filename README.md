![banner](assert.png)

# Armazenamento-Manipula-o-e-Transforma-o-de-Dados.
![MySQL](https://img.shields.io/badge/Database-MySQL-blue)
![SQL](https://img.shields.io/badge/Language-SQL-orange)
![ETL](https://img.shields.io/badge/Process-ETL-success)
![Data Engineering](https://img.shields.io/badge/Area-Data%20Engineering-purple)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

Projeto completo de **engenharia e análise de dados** utilizando **MySQL**, desenvolvido a partir do **dataset público da Olist**, um dos maiores e-commerces do Brasil.

O projeto segue a metodologia **STAR (Situation, Task, Action, Result)**, amplamente utilizada em contextos profissionais, garantindo clareza na comunicação técnica e foco em resultados.

---

## 🧠 Visão Geral do Projeto

- 🔹 Modelagem relacional de dados
- 🔹 Processo ETL (Extract, Transform, Load)
- 🔹 Limpeza, padronização e tratamento de dados
- 🔹 Otimização de performance com índices
- 🔹 Consultas analíticas orientadas a negócio

Este repositório demonstra habilidades práticas em **SQL**, **modelagem de dados**, **qualidade da informação** e **engenharia de dados aplicada**.

---

## 📌 Metodologia STAR

### 🔹 Situation (Situação)

O projeto iniciou-se com um grande volume de dados transacionais distribuídos em múltiplos arquivos CSV, contemplando diferentes áreas do negócio:

- Clientes  
- Pedidos  
- Itens de pedidos  
- Pagamentos  
- Produtos  
- Vendedores  
- Avaliações  
- Geolocalização  

Os dados encontravam-se em estado bruto, apresentando diversos problemas comuns em ambientes reais, como:

- Valores nulos e campos vazios  
- Tipos de dados inconsistentes  
- Registros duplicados  
- Ausência de índices  
- Falta de estrutura analítica  

Essas limitações impediam análises confiáveis e dificultavam a geração de insights de negócio.

---

### 🔹 Task (Tarefa)

O objetivo foi construir uma **base de dados relacional robusta**, confiável e performática, capaz de suportar análises exploratórias, relatórios gerenciais e futuras soluções de Business Intelligence.

Principais responsabilidades:

- Modelar entidades e relacionamentos
- Criar tabelas relacionais normalizadas
- Realizar carga de dados a partir de arquivos CSV
- Tratar inconsistências, nulos e duplicidades
- Otimizar consultas com índices
- Desenvolver queries analíticas orientadas ao negócio

---

### 🔹 Action (Ação)

As ações foram executadas em etapas bem definidas, garantindo rastreabilidade e controle das transformações.

#### 1️⃣ Modelagem de Dados

Criação de tabelas relacionais representando as principais entidades do ecossistema Olist, com definição adequada de:

- Tipos de dados  
- Chaves primárias e relacionamentos  
- Estrutura preparada para análise  

---

#### 2️⃣ Carga de Dados (ETL – Extract & Load)

Importação eficiente dos arquivos CSV utilizando:

```sql
LOAD DATA LOCAL INFILE
Com padronização de:

Delimitadores

Aspas

Encoding

3️⃣ Limpeza e Transformação dos Dados
Principais ações realizadas:

Conversão de campos vazios para NULL

Remoção de registros completamente inválidos

Ajuste de tipos e tamanhos de colunas

Identificação de duplicidades por chaves de negócio

Exclusão segura de registros duplicados

4️⃣ Otimização de Performance
Criação de índices em colunas estratégicas

Validação de unicidade

Remoção de índices temporários após uso

Resultado: consultas significativamente mais rápidas e eficientes.

5️⃣ Consultas Analíticas
Foram desenvolvidas consultas para responder perguntas relevantes, como:

⏱ Tempo de aprovação de pedidos

📅 Compras por dia da semana

🚚 Tempo médio de entrega

👤 Classificação de clientes por recorrência

💰 Valor total dos pedidos

🔹 Result (Resultado)
Resultados alcançados com o projeto:

✔ Base de dados limpa, estruturada e confiável

✔ Redução expressiva de inconsistências e duplicidades

✔ Melhoria significativa no desempenho das consultas SQL

✔ Dados prontos para análises, dashboards e BI

✔ Estrutura escalável para Data Warehouses

Este projeto evidencia domínio de SQL avançado, modelagem relacional e boas práticas de engenharia de dados, sendo altamente relevante para portfólios profissionais.

🛠 Tecnologias Utilizadas
MySQL

SQL (DDL, DML e consultas analíticas)

Dataset público da Olist

🚀 Possíveis Evoluções
Construção de um Data Warehouse

Integração com Power BI, Tableau ou Looker

Automação de pipelines ETL

Criação de dashboards analíticos

👩‍💻 Autora
Yorrana Souza Santos
Projeto desenvolvido para fins de estudo, prática profissional e portfólio em Análise e Engenharia de Dado
