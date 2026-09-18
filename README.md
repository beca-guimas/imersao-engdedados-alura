# ⚡ Imersão Engenharia de Dados com IA - Alura (Projeto ANAC)

Repositório dedicado ao desenvolvimento do pipeline de dados construído durante a Imersão em Engenharia de Dados da Alura. O projeto consistiu na criação de um ecossistema completo de ETL utilizando dados públicos de aviação da ANAC.

## 🛠️ Ferramentas e Tecnologias
* **Ambiente de Desenvolvimento:** Databricks
* **Linguagem Principal:** Python
* **Motor de Processamento:** PySpark & Spark SQL
* **Formatos & Armazenamento:** Delta Lake (Tabelas Delta)
* **Arquitetura de Dados:** Conceito de Arquitetura Medalhão (Bronze, Silver e Gold)

## 📂 Estrutura do Repositório
* `notebooks/`: Arquivos contendo os códigos dos notebooks desenvolvidos e exportados do Databricks.
* `pipelines/`: Scripts com os fluxos automatizados de transformação de dados.
* `sql/`: Consultas em Spark SQL contendo os gabaritos e métricas criadas para os desafios.

## 🏆 Desafios Concluídos
* **Desafio 1 (Camada Bronze):** Ingestão, carga e organização dos dados brutos de voos da ANAC para tabelas iniciais.
* **Desafio 2 (Camada Silver):** Limpeza, refinamento e tratamento dos dados estruturados utilizando PySpark.
* **Desafio 3 (Camada Gold):** Criação de tabelas analíticas agregadas via Spark SQL para extração de métricas de negócio e IA.
