# Engenheiro de Machine Learning

## [1. O que é Machine Learning?](#machine_learning)
- Dados
- Algoritmos
- Modelo
- Treinamento
- Inferência

## [2. O que é MLOps?](#mlops)
- Explicação

## [2. Fundamentos de Machine Learning](#fundamentos_machine_learning)
- Aprendizado Supervisionado
- Aprendizado Não Supervisionado
- Regressão
- Classificação
- Agrupamento (Clustering)

## 3. Matemática para ML
- Álgebra Linear
- Cálculo
- Estatística
- Probabilidade

## 4. Deep Learning
- Redes Neurais
- Redes Neurais Convolucionais (CNN)
- Redes Neurais Recorrentes (RNN)
- Long Short-Term Memory (LSTM)
- Transfer Learning

## 4. MLOps
- Deploy de Modelos
- Versionamento de Modelos
- Monitoramento de Modelos
- Pipelines
- Integração e Entrega Contínua (CI/CD)

## 5. Processamento de Dados
- Limpeza de Dados
- Engenharia de Features
- Redução de Dimensionalidade
- Pipelines de Dados

## 6. Ferramentas e Frameworks
- TensorFlow
- PyTorch
- Scikit-learn
- Docker
- MLflow

## 7. Projetos e Aplicações do Mundo Real
- Estudos de Caso
- Otimização de Modelos
- Inferência em Tempo Real
- Impacto no Negócio

<a id="machine_learning"></a>

# O que é Machine Learning?

**Machine Learning** (ML) é um campo da inteligência artificial (IA) que se concentra no desenvolvimento de algoritmos e modelos que permitem que computadores aprendam a partir de dados e tomem decisões ou façam previsões sem serem explicitamente programados para isso. Em vez de seguir instruções rígidas, os sistemas de Machine Learning analisam grandes volumes de dados, identificam padrões, e, com base nisso, realizam tarefas específicas de maneira autônoma.

### Componentes principais do Machine Learning:

- **Dados:** O combustível dos modelos de Machine Learning. Grandes quantidades de dados são necessárias para que os algoritmos aprendam. Esses dados podem ser rotulados (supervisionados) ou não rotulados (não supervisionados).

- **Algoritmos:** Conjuntos de regras e fórmulas matemáticas que processam os dados e identificam padrões. Diferentes algoritmos são usados para diferentes tipos de problemas, como regressão, classificação, clustering, etc.

- **Modelo:** Após o treinamento com dados, o algoritmo gera um modelo. O modelo é a representação da relação entre os dados de entrada e os resultados previstos.

- **Treinamento:** Processo em que o algoritmo ajusta seus parâmetros internos com base nos dados de entrada para melhorar sua capacidade de fazer previsões ou tomar decisões corretas.

- **Inferência:** Uma vez treinado, o modelo pode ser usado para fazer previsões sobre novos dados que não foram vistos durante o treinamento.

<a id="fundamentos_machine_learning"></a>

# Fundamentos de Machine Learning

Os Fundamentos de Machine Learning referem-se aos conceitos essenciais que formam a base do aprendizado de máquina. Esses fundamentos são importantes para entender como os algoritmos de Machine Learning funcionam e como eles podem ser aplicados para resolver problemas. Aqui estão os principais componentes:
1. Aprendizado Supervisionado

    Definição: Um tipo de aprendizado onde o modelo é treinado com dados rotulados, ou seja, para cada entrada, há uma saída conhecida.
    Exemplo: Um algoritmo recebe um conjunto de dados de casas com características como tamanho, localização e preço. Ele aprende a mapear essas características para o preço e, com isso, pode prever o preço de novas casas.
    Aplicações: Classificação (ex: detecção de spam) e regressão (ex: prever preços).

2. Aprendizado Não Supervisionado

    Definição: Aqui o modelo é treinado com dados não rotulados. O objetivo é identificar padrões ocultos ou estruturas nos dados.
    Exemplo: Agrupar clientes com base em comportamentos semelhantes (clustering), sem saber de antemão a quais grupos pertencem.
    Aplicações: Segmentação de clientes, detecção de anomalias.

3. Regressão

    Definição: É um tipo de problema de aprendizado supervisionado em que o objetivo é prever um valor contínuo.
    Exemplo: Prever a temperatura para o próximo dia com base nos dados históricos de temperatura.
    Algoritmos Comuns: Regressão linear, regressão polinomial.

4. Classificação

    Definição: Outro tipo de problema de aprendizado supervisionado, mas aqui o objetivo é prever uma classe ou categoria.
    Exemplo: Dado um e-mail, o modelo decide se ele é spam ou não spam (duas classes).
    Algoritmos Comuns: Regressão logística, árvores de decisão, SVM.

5. Agrupamento (Clustering)

    Definição: Técnica de aprendizado não supervisionado onde o objetivo é agrupar dados semelhantes. O algoritmo tenta descobrir a estrutura subjacente dos dados sem rótulos.
    Exemplo: Agrupar filmes com base em temas ou características semelhantes.
    Algoritmos Comuns: K-Means, DBSCAN, Hierarchical Clustering.

<a id="mlops"></a>
# O que é MLOps?

MLOps é uma cultura e prática de engenharia que busca unificar desenvolvimento de sistemas de ML (Dev) e operação de sistemas de ML (Ops).
MLOps encoraja fortemente a automação e monitoramento de todos os passos da construção e operação de um sistema de ML, desde a integração, testes, promoção a produção a manutenção da infraestrutura.

# O que é Feature Store?