# Análise de Vendas e Churn Target Brasil


#### Este repositório foi utilizado para praticar habilidades, contém notebooks e pipelines para análise e tratamento de dados de vendas e churn, com foco em processos de ETL (Extração, Transformação e Carregamento) para preparação de dados. Estes dados são do E-commerce da Target Brasil, retirados da plataforma Kaggle.
Abaixo, estão descritas as principais pastas e arquivos incluídos:

## ETL/

- #### pipeline_silver.ipynb:
  Notebook responsável pela primeira fase do pipeline ETL. Ele extrai e transforma dados brutos, salvando-os na camada "Silver". Nesta etapa, são realizadas limpezas básicas e transformações iniciais para preparar os dados para análises mais avançadas, com base nas observações da análise exploratória.

- #### pipeline_gold.ipynb:
  Notebook responsável pela segunda fase do pipeline ETL. Ele carrega e refina os dados da camada "Silver", aplicando transformações adicionais e cálculos de métricas para gerar tabelas finais na camada "Gold", prontas para análise e visualização no Power BI.

## notebooks/

- #### Análise_exploratória_vendas_e_churn.ipynb:
  Notebook de análise exploratória de dados de vendas e churn. Essa análise foi feita primeiro para entender a estrutura dos dados e identificar padrões, o que guiou as etapas de limpeza e transformação aplicadas nas pipelines das camadas Bronze e Silver.

- #### tentativa_reg_logística_churn.ipynb:
  Notebook com uma tentativa de modelagem de regressão logística para prever o churn de clientes. Inclui a preparação dos dados, treinamento do modelo e avaliação de desempenho.
