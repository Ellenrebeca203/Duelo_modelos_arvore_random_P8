# Duelo_modelos_previsao_compras_P8

## OBJETIVO:
Desenvolver um modelo preditivo capaz de analisar os padrões de comportamento dos clientes e identificar sinais que indicam a propensão deles para realizar compras no site da empresa. Para isso, vamos usar uma base de dados que contém informações detalhadas sobre os clientes.

## DADOS DA BASE:
- Year_Birth: Ano de nascimento do cliente.

- Education: Nível de escolaridade do cliente.

- Marital_Status: Estado civil do cliente.

- Income: Renda anual da família do cliente.

- Kidhome: Número de crianças na casa do cliente.

- Recency: Número de dias desde a última compra do cliente.

- Complain: 1 se o cliente reclamou nos últimos 2 anos, 0 caso contrário.

- MntWines: Valor gasto em vinhos nos últimos 2 anos.

- MntFruits: Valor gasto em frutas nos últimos 2 anos.

- MntMeatProducts: Valor gasto em carnes nos últimos 2 anos.

- MntFishProducts: Valor gasto em peixes nos últimos 2 anos.

- MntSweetProducts: Valor gasto em doces nos últimos 2 anos.

- MntGoldProds: Valor gasto em produtos de ouro nos últimos 2 anos.

- NumDealsPurchases: Número de compras feitas com desconto

- NumStorePurchases: Número de compras feitas diretamente nas lojas.

- NumWebVisitsMonth: Número de visitas ao site da empresa no último mês.

- **WebPurchases: Se o cliente fez ou não a compra, 1 indica que sim, 0 indica que não (VARIÁVEL ALVO)**


## ETAPAS DO PROJETO:

## Etapa 1: Preparação dos Dados

- **Exploração e Limpeza:** Foi feita a analise e limpeza dos dados tratando dados nulos para garantir que estivessem prontos para a modelagem.
- **Análise:** Foi construido o storytelling através gráficos, para entender a dispersão e presença de Outliers, analisando e retirando insights das informações.

## Etapa 2: Pré-processamento:

- **Análise Correlação:** Verificação e observação das correlações entre as váriaveis e análise.

- **Codificação de Variáveis Categóricas:** Transformação de variáveis categóricas para aplicação posterior em modelo. 

- **Separe a base em Y, X e Treino e teste:**: Separação dos dados de treino e teste.

- **Realize a padronização dos dados**: Feita a padronização dos dados para garantir eficiência no modelo e eficácia.


## Etapa 3: Modelagem

- **Escolha dos modelos:** Foram selecionados dois modelos o Random Forest e a Árvore de Decisão
- **Melhoria dos modelos:** Foram selecionadas variávies atrave´s do 'feature importance' para treinar o modelo com as melhores variáveis possíveis afim de realizar melhores previsões.


## Etapa 4: Avaliação dos modelos

-**Avaliação:** Foi avaliado os resultados com as métricas padrões nos dois modelos e identificado o melhor nas previsões.


## CONCLUSÃO
Foram escolhidos dois modelos para treinar os dados da base. Sendo eles o Random Forest e a Árvore de Decisão. Inicialmente o Random Forest apresentou uma acurácia geral de 0.8842676311030742, então foi escolhido fazer o feature importance, e houve uma melhoria considerável na acurácia 0.91. O segundo modelo treinado como já mencionado foi a Árvore de Decisão, que inicialmente uma acurácia de 0.8679927667269439 (sendo menor que a do Random Forest), porém ao selecionar o feature importance e retreinar o modelo com features melhores, a acurácia subiu para 0.92 ultrapassando Random Forest, portanto o melhor modelo para esses dados da base foi a Árvore de Decisão com o feature importance.  


**WebPurchases: Número de compras feitas pelo site da empresa.**
