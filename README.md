# challenge-telecom-x-1-alura

**análise de evasão de clientes (churn)**

1 - descrição do projeto

Este projeto tem como objetivo analisar a evasão de clientes (churn) em uma empresa de telecomunicações. A evasão representa o cancelamento do serviço por parte do cliente e é um dos principais desafios para empresas que trabalham com modelos de assinatura ou serviços recorrentes.

A análise foi realizada utilizando Python e bibliotecas de análise de dados, com foco em compreender padrões associados ao cancelamento de clientes e identificar possíveis fatores relacionados ao churn.

2 - fonte dos dados

Os dados utilizados no projeto foram obtidos por meio de uma API pública fornecida para o desafio Telecom X. A base contém informações demográficas, contratuais e financeiras dos clientes.

Entre as principais categorias de dados estão:

- informações demográficas dos clientes
- tipo de contrato
- serviços de internet e telefonia
- métodos de pagamento
- valores de cobrança mensal e total
- tempo de permanência do cliente
- status de churn

3 - etapas do projeto

O projeto foi dividido em três principais etapas:

extração de dados  
transformação e limpeza  
análise exploratória de dados

Durante a etapa de extração, os dados foram obtidos via requisição HTTP e convertidos para um DataFrame utilizando a biblioteca pandas.

Na etapa de transformação, foram realizadas diversas operações de limpeza e padronização dos dados, incluindo tratamento de valores nulos, correção de tipos de dados e padronização de colunas categóricas.

Por fim, foi realizada uma análise exploratória de dados (EDA) utilizando estatísticas descritivas e visualizações para identificar padrões associados ao churn.

4 - principais análises realizadas

Durante a análise exploratória foram avaliados diferentes aspectos dos dados, incluindo:

distribuição geral de clientes com e sem churn  
comparação do churn entre diferentes categorias de clientes  
análise de variáveis numéricas como tempo de contrato e valor total gasto  
cálculo de estatísticas descritivas como média, mediana e desvio padrão  

Também foi criada uma variável adicional chamada contas_diarias, calculada a partir do valor mensal cobrado do cliente.

5 - principais insights

A análise revelou alguns padrões importantes relacionados à evasão de clientes:

clientes com menor tempo de contrato apresentam maior probabilidade de cancelar o serviço  
clientes que cancelam tendem a apresentar menor valor total gasto  
variáveis demográficas como gênero não apresentaram diferença significativa entre clientes que cancelaram e os que permaneceram  

Esses resultados sugerem que o período inicial do relacionamento com o cliente é um momento crítico para retenção.

6 - ferramentas utilizadas

O projeto foi desenvolvido utilizando as seguintes ferramentas e bibliotecas:

Python  
pandas  
matplotlib  
seaborn  
requests  

7 - possíveis extensões do projeto

Este projeto pode ser expandido com novas análises e técnicas mais avançadas, como:

criação de modelos preditivos de churn utilizando machine learning  
análise de correlação entre variáveis  
construção de dashboards interativos para monitoramento de churn  
segmentação de clientes com técnicas de clusterização
