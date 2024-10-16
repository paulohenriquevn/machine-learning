# A preparação e transformação de dados

A preparação e transformação de dados é uma etapa crítica no pipeline de machine learning, onde os dados brutos são convertidos em um formato adequado para alimentar algoritmos de aprendizado. Como descrito no guia de certificação AWS Certified Machine Learning Specialty, essa fase consome uma parte significativa do tempo do projeto de machine learning, pois os modelos de aprendizado dependem fortemente da qualidade dos dados para gerar resultados precisos e relevantes.
Objetivo da Preparação e Transformação de Dados

## Objetivo da Preparação e Transformação de Dados

O principal objetivo dessa etapa é transformar dados não estruturados ou semi-estruturados em um formato estruturado e limpo, permitindo que o modelo possa identificar padrões e gerar previsões. A preparação adequada reduz a possibilidade de viés, overfitting, ou underfitting no modelo, assegurando que ele consiga generalizar bem para novos dados.
Subprocessos na Preparação e Transformação de Dados

# Subprocessos na Preparação e Transformação de Dados

## 1. Identificação e Seleção de Features

### 1.1 Features: 
são as variáveis que representam o problema que o modelo deve resolver. A escolha das features certas é um fator determinante para o sucesso de um modelo. Nesta etapa, os engenheiros de machine learning precisam selecionar cuidadosamente as variáveis relevantes e remover as irrelevantes.

### 1.2 Transformação de Features Categóricas:

Variáveis categóricas (como rótulos, nomes de categorias ou classificações) não podem ser usadas diretamente por muitos algoritmos de ML. Assim, elas precisam ser transformadas em variáveis numéricas.

* Técnicas:

    * Codificação One-Hot: Transforma categorias em variáveis binárias.
    * Codificação Ordinal: Atribui números inteiros a categorias com hierarquia.
    * Codificação Binária: Transforma categorias em códigos binários para lidar com grandes conjuntos categóricos.

### 1.3 Transformação de Features Numéricas:
* Normalização 

    Escala os dados numéricos para que todos fiquem dentro do mesmo intervalo (geralmente entre 0 e 1). Isso é especialmente útil para algoritmos sensíveis à escala dos dados, como redes neurais e regressão logística.

* Padronização 

    Converte os dados para terem média zero e desvio padrão unitário. Frequentemente utilizada em modelos de aprendizado baseados em gradientes.

* Binning ou Discretização

    Transformação de variáveis numéricas contínuas em variáveis discretas, dividindo o intervalo de valores em "bins".

* Tratamento de Dados Ausentes

    É comum lidar com valores ausentes em datasets reais. Existem várias estratégias para lidar com esse problema:

* Imputação 

   Substituir valores ausentes pela média, mediana ou moda.

* Imputação com Algoritmos de ML
   
   Usar técnicas mais sofisticadas, como KNN ou regressão, para prever e preencher os valores ausentes.

* Exclusão de registros

   Remover registros que contenham dados ausentes (usado com cautela, pois pode levar à perda de dados importantes).

### 1.4 Lidando com Outliers:

Outliers podem distorcer os resultados de muitos modelos de machine learning. Esses valores atípicos podem ser removidos ou transformados para que não causem impacto excessivo.

* Técnicas comuns

   Limites manuais, Z-Score, ou substituição dos outliers por valores mais plausíveis.

* Tratamento de Conjuntos de Dados Desbalanceados

  Quando há um desbalanceamento significativo nas classes de saída (por exemplo, em um problema de classificação binária onde 95% dos exemplos pertencem a uma classe e apenas 5% à outra), o modelo pode aprender a favorecer a classe majoritária. Técnicas como oversampling (replicar instâncias da classe minoritária) e undersampling (reduzir instâncias da classe majoritária) são utilizadas para combater esse problema.

* Técnicas avançadas: 

   SMOTE (Synthetic Minority Over-sampling Technique), que cria exemplos sintéticos para a classe minoritária.

* Transformação de Dados Textuais

  O livro também aborda a preparação de dados textuais, um tipo específico de dados não estruturados. Técnicas como Bag of Words (BoW), TF-IDF (Term Frequency-Inverse Document Frequency) e Word Embedding (vetorização de palavras, como Word2Vec ou GloVe) são cruciais para transformar texto em representações numéricas que podem ser compreendidas pelos algoritmos de ML.