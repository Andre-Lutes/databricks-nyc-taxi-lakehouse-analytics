\# Databricks NYC Taxi Lakehouse Analytics



\## 🇧🇷 Português



Projeto prático de Lakehouse Analytics desenvolvido no Databricks, utilizando dados públicos e reais de corridas de táxi de Nova York.



O objetivo do projeto foi construir um pipeline de dados completo com PySpark, Delta Lake e SQL, seguindo uma arquitetura em camadas Bronze, Silver e Gold.



Este projeto reforça habilidades práticas em engenharia/analytics de dados, tratamento de dados reais, criação de métricas de negócio e consultas analíticas em SQL.



\---



\## Objetivo do projeto



Construir um pipeline Lakehouse no Databricks para ingestão, tratamento, enriquecimento e análise de dados reais de viagens de táxi.



O projeto cobre:



\- Ingestão de dados públicos em formato Parquet

\- Upload dos arquivos para Volume no Databricks

\- Leitura com PySpark

\- Criação de tabelas Delta na camada Bronze

\- Limpeza e tratamento dos dados na camada Silver

\- Enriquecimento com dados de zonas geográficas

\- Criação de tabelas Gold com métricas de negócio

\- Consultas SQL para análise executiva



\---



\## Dataset



Fonte dos dados:



NYC Taxi \& Limousine Commission - Yellow Taxi Trip Records



Arquivo utilizado:



\- `yellow\_tripdata\_2024-01.parquet`

\- `taxi\_zone\_lookup.csv`



A base principal contém aproximadamente 3 milhões de registros de corridas de táxi em janeiro de 2024.



\---



\## Arquitetura do projeto



```text

Raw Files

&#x20;  ↓

Bronze Delta Tables

&#x20;  ↓

Silver Cleaned Tables

&#x20;  ↓

Silver Enriched Table

&#x20;  ↓

Gold Business Metrics

&#x20;  ↓

SQL Analytics

