# Telecom X — Parte 2
Visão Geral

Este projeto tem como objetivo analisar e prever a evasão de clientes (Churn) na empresa fictícia Telecom X utilizando técnicas de análise de dados e Machine Learning.

A evasão de clientes é um problema crítico para empresas de telecomunicações, pois impacta diretamente a receita e o crescimento do negócio. A partir da análise exploratória dos dados e da construção de modelos preditivos, buscamos identificar os principais fatores que levam os clientes a cancelar seus serviços e propor estratégias para reduzir esse comportamento.

Objetivos do Projeto

O projeto foi desenvolvido com os seguintes objetivos:

Analisar os dados de clientes da Telecom X

Identificar padrões associados à evasão de clientes

Construir modelos de Machine Learning para prever churn

Avaliar o desempenho dos modelos utilizando métricas adequadas

Identificar as variáveis mais importantes para a previsão

Propor estratégias de retenção de clientes com base nos resultados obtidos

Tecnologias Utilizadas

As principais tecnologias e bibliotecas utilizadas neste projeto foram:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

Estrutura do Projeto
telecom-churn-analysis/
│
├── dados_tratados.csv
├── Telecon_X_2.ipynb
├── README.md

Descrição dos arquivos:

dados_tratados.csv: Dataset tratado utilizado na análise e modelagem.

Telecon_X_2.ipynb: Notebook contendo todo o processo de análise e modelagem.

README.md: Documentação do projeto.

Etapas do Projeto
1. Importação e Limpeza dos Dados

Os dados foram carregados a partir de um arquivo CSV previamente tratado. Durante essa etapa foram realizadas verificações de:

valores ausentes

tipos de dados

colunas irrelevantes

conversão de variáveis categóricas em variáveis numéricas utilizando one-hot encoding

Análise Exploratória de Dados (EDA)

A análise exploratória foi realizada para entender melhor o comportamento dos clientes e identificar padrões associados à evasão.

Entre as principais análises realizadas estão:

Distribuição da variável Churn

Matriz de correlação entre variáveis

Análise do tempo de permanência do cliente

Análise do valor total gasto

Visualizações utilizando boxplots e scatter plots

Essas análises permitiram identificar variáveis que possuem maior relação com o churn.

Modelos de Machine Learning

Foram utilizados dois modelos diferentes para prever a evasão de clientes.

Regressão Logística

A Regressão Logística foi escolhida por ser um modelo simples e interpretável para problemas de classificação binária.

Como este modelo é sensível à escala das variáveis, foi aplicada normalização dos dados utilizando StandardScaler.

Principais vantagens:

Interpretabilidade

Facilidade de implementação

Boa performance em problemas lineares

Random Forest

O Random Forest é um modelo baseado em árvores de decisão que combina diversas árvores para melhorar a capacidade de generalização.

Esse modelo não é sensível à escala das variáveis, portanto não exige normalização.

Principais vantagens:

Captura relações complexas

Alta capacidade preditiva

Robustez contra overfitting

Avaliação dos Modelos

Os modelos foram avaliados utilizando as seguintes métricas:

Acurácia

Precisão

Recall

F1-score

Matriz de confusão

Essas métricas permitem avaliar tanto a taxa geral de acertos quanto a capacidade do modelo de identificar corretamente clientes que irão cancelar o serviço.

De modo geral, o modelo Random Forest apresentou melhor desempenho, demonstrando maior capacidade de capturar padrões complexos nos dados.

Variáveis Mais Importantes

A análise da importância das variáveis revelou fatores relevantes para a previsão da evasão de clientes.

Entre as principais variáveis destacam-se:

Tempo de permanência do cliente

Valor da cobrança mensal

Valor total gasto

Características do perfil do cliente

Tipo de serviços contratados

Essas variáveis desempenham papel importante na decisão de cancelamento.

Estratégias de Retenção de Clientes

Com base nos resultados obtidos, algumas estratégias podem ser adotadas para reduzir a evasão:

Criar programas de fidelização para clientes mais novos

Oferecer planos personalizados para clientes com maior risco de churn

Ajustar preços e benefícios de determinados planos

Implementar modelos preditivos para identificar clientes com maior probabilidade de cancelamento

Como Executar o Projeto

Clone o repositório

git clone (https://github.com/EvertonSantos3/Chalenge-TeleconX---Parte-2)

Acesse o diretório do projeto

cd Telecon_X_2.ipynb

Abra o notebook no Google Colab ou Jupyter Notebook

Execute as células na ordem apresentada.

Resultados

Os resultados obtidos mostram que modelos de Machine Learning podem ser utilizados com sucesso para prever a evasão de clientes.

A utilização dessas técnicas permite que empresas identifiquem clientes com maior risco de churn e tomem decisões estratégicas baseadas em dados.

Conclusão

Este projeto demonstrou como técnicas de análise de dados e Machine Learning podem ser aplicadas para compreender e prever o comportamento de clientes em empresas de telecomunicações.

Além de prever a evasão de clientes, a análise permitiu identificar fatores críticos que podem orientar estratégias de retenção e melhorar a tomada de decisão baseada em dados.

Autor Everton

Projeto desenvolvido como parte de um desafio de Análise de Dados e Machine Learning.
