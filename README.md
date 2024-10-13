## Índice de Projetos

###  Engenharia de Dados
- **[PySpark-Medalhao-Azure-ETL-Pipeline](https://github.com/RossetoAnalytics/Arq-Medalhao-AzureDatabricks)**  
  Projeto desenvolvido criando um ETL a partir de um host local do SQL Server, usando Azure e Databricks em uma configuração de um ambiente de produção. Este projeto faz uso de vários recursos da Azure, como o gerenciamento de permissões, Azure Data Lake Storage Gen2 (ADLS2), Azure Active Directory (AAD), conectores, Data Factory, Azure Synapse Analytics, conteúdos dinâmicos para queries automáticas e dinâmicas, Key Vault para guardar segredos. Além de PySpark e SQL, o workspace do Databricks foi utilizado para criar transformações de dados em uma arquitetura medalhão, aproveitando as capacidades do PySpark para processamento e transformação em escala.

<details>
  <summary>Diagrama</summary>

  ![371883148-711fa6c8-4c8a-4eec-bb1f-c4f13e556c79](https://github.com/user-attachments/assets/5cfff45a-a71a-4c07-b1bd-6b8c07567424)


</details>


- **[DBT Data Lake Project](https://github.com/RossetoAnalytics/DBT-Data-Lake-Project)**  
  Este projeto foi desenvolvido utilizando vários recursos do DBT-Core e configurações do PostgreSQL em um RDS da AWS. O DBeaver foi utilizado como sistema de gerenciamento local. O projeto gera tabelas usando a biblioteca Faker, seguindo uma arquitetura de Data Lake.

<details>
  <summary>Linaege on DBT-Core localhost catalog</summary>

 ![dbt-marts-run-lineage](https://github.com/user-attachments/assets/c1ad890c-8a2f-40cb-a016-a9ba6863e591)


</details>

- **[Ingestao Incremental Streaming](https://github.com/RossetoAnalytics/Ingestao-Incremental-Streaming)**  
  O Auto Loader é um recurso do Apache Spark que facilita a ingestão incremental de dados em tempo real. Ele permite a leitura automática de novos arquivos em um diretório (sistema de arquivos, podendo conter diversos formatdos), aplicando um esquema definido e gerenciando checkpoints para garantir a consistência dos dados. Esses dados (arquivos .json nesse projeto) são então carregados em uma tabela em um banco de dados.

<details>
  <summary>Checkpoints para ingestão incremental atômica</summary>
  
![checkpoints_autoloader](https://github.com/user-attachments/assets/86dcdd98-70be-4114-be2b-79d946377e82)

</details>


- **[Airflow-Cotações](https://github.com/RossetoAnalytics/airflow-cotacoes)**  
  Este projeto foi desenvolvido para demonstrar a criação e implementação de uma Directed Acyclic Graph (DAG) utilizando Apache Airflow. O foco foi a ingestão e transformação de dados do Banco Central do Brasil relacionados à cotação de moedas, com o objetivo de automatizar o download e o processamento desses dados a partir de um arquivo CSV disponível em um endpoint público.

<details>
  <summary>DAG</summary>

   ![dag_fin_cotacoes_bcb](https://github.com/user-attachments/assets/e3175878-cc25-4c3c-bed1-4738d52f8e43)

</details>
  
  
- **[Churn Buster: Análise de Engajamento](https://github.com/RossetoAnalytics/NeobankAnalysis)**  
  A missão deste projeto é revelar insights, fornecer recomendações de negócios inteligentes para reduzir as taxas de churn e iluminar caminhos para aumentar o envolvimento dos usuários. Utilizo ferramentas como SQL, Python, Excel e Power BI para limpeza, transformação e visualização dos dados.

 <details>
    <summary>Diagrama</summary>
  
![image](https://github.com/user-attachments/assets/ae0b93d7-e2cb-4e90-a522-6a0ca0dba505)


 </details>

###  Análise/Ciência de Dados
- **[Análise de comportamento de usuário de E-commerce](https://github.com/RossetoAnalytics/E-Commerce-Behavior-Analysis)**  
  Análise de comportamento de clientes de um e-commerce, com foco em identificar perfis com maior gasto total. Utilizei técnicas de EDA e teste de hipóteses.

- **[Análise de Outliers](https://github.com/RossetoAnalytics/EPA-Probabilidade-Outliers)**  
  Análise de probabilidade com identificação de outliers em dados de qualidade do ar, utilizando a regra empírica e o IQR.

- **[Churn Buster: Análise de Engajamento](https://github.com/RossetoAnalytics/NeobankAnalysis)**  
  A missão deste projeto é revelar insights, fornecer recomendações de negócios inteligentes para reduzir as taxas de churn e iluminar caminhos para aumentar o envolvimento dos usuários. Utilizo ferramentas como SQL, Python, Excel e Power BI para limpeza, transformação e visualização dos dados.

 <details>
    <summary>Diagrama</summary>
  
![image](https://github.com/user-attachments/assets/ae0b93d7-e2cb-4e90-a522-6a0ca0dba505)


 </details>

