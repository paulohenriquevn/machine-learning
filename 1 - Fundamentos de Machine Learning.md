# Fundamentos de Machine Learning

## 1. Inteligência Artificial (IA), Machine Learning (ML) e Deep Learning (DL)

- **IA (Inteligência Artificial)**: Área da ciência que busca simular a inteligência humana por meio de sistemas computacionais.
- **ML (Machine Learning)**: Subcampo da IA que permite a sistemas aprenderem com dados e fazer previsões ou decisões sem programação explícita.
- **DL (Deep Learning)**: Subcampo do ML que utiliza redes neurais profundas para resolver problemas complexos, como visão computacional e processamento de linguagem natural.

**Exemplo**: O impacto do aumento da capacidade computacional no crescimento de aplicações de IA e ML.

---

## 2. Tipos de Aprendizado em Machine Learning

### 2.1 Aprendizado Supervisionado
- **Definição**: O modelo é treinado com dados rotulados, onde as saídas são conhecidas.
- **Exemplos**: Regressão Linear, Regressão Logística, Classificação (SVM, kNN).

**Exemplo de Aplicação**: Classificação de e-mails como "spam" ou "não-spam".

### 2.2 Aprendizado Não Supervisionado
- **Definição**: O modelo trabalha com dados não rotulados, buscando padrões ou grupos nos dados.
- **Exemplos**: Clusterização (K-Means), Redução de Dimensionalidade (PCA).

**Exemplo de Aplicação**: Segmentação de clientes com base em hábitos de compra.

### 2.3 Aprendizado por Reforço
- **Definição**: O modelo aprende interagindo com um ambiente e é recompensado ou penalizado com base nas suas ações.
  
**Exemplo de Aplicação**: Algoritmos de jogos, como AlphaGo.

---

## 3. Pipeline de Machine Learning (Ciclo CRISP-DM)

1. **Entendimento do Negócio**: Definir os objetivos e problemas a serem resolvidos com ML.
2. **Entendimento dos Dados**: Coleta e análise dos dados disponíveis.
3. **Preparação dos Dados**: Limpeza, tratamento de outliers e criação de novas features.
4. **Modelagem**: Seleção e treinamento de algoritmos apropriados.
5. **Avaliação**: Verificação da qualidade do modelo com métricas apropriadas.
6. **Implantação**: Colocar o modelo em produção e monitorá-lo.

**Exemplo**: Aplicar o ciclo CRISP-DM em projetos de previsão de vendas.

---

## 4. Divisão de Dados (Treinamento, Validação, Teste)

- **Conjunto de Treinamento**: Usado para treinar o modelo.
- **Conjunto de Validação**: Usado para ajustar hiperparâmetros e evitar overfitting.
- **Conjunto de Teste**: Usado para avaliar o modelo em dados que ele nunca viu.

**Conceitos Importantes**:
- **Overfitting**: Quando o modelo se ajusta demais aos dados de treinamento e não generaliza bem.
- **Underfitting**: Quando o modelo é muito simples e não captura os padrões dos dados.

---

## 5. Algoritmos Supervisionados e Não Supervisionados

### 5.1 Algoritmos de Classificação
- **Definição**: Previsão de classes ou categorias.
- **Exemplos**: Árvores de Decisão, SVM, Redes Neurais.

### 5.2 Algoritmos de Regressão
- **Definição**: Previsão de valores contínuos.
- **Exemplos**: Regressão Linear, Regressão Polinomial.

### 5.3 Algoritmos de Clusterização
- **Definição**: Agrupamento de dados com base em suas características.
- **Exemplos**: K-Means, DBSCAN.

**Exemplo**: Comparar diferentes algoritmos para prever vendas ou segmentar clientes.

---

## 6. Bias vs. Variância

- **Bias (Viés)**: Erro devido a simplificações excessivas no modelo (underfitting).
- **Variância**: Erro causado por um modelo que se ajusta demais aos dados de treinamento (overfitting).

**Objetivo**: Encontrar um equilíbrio entre bias e variância para minimizar o erro total.

---

## 7. Validação Cruzada e Regularização

### 7.1 Validação Cruzada (k-fold)
- **Definição**: Técnica que divide os dados em k subconjuntos para treinar e validar o modelo várias vezes.
- **Exemplo**: k-fold cross-validation.

### 7.2 Regularização
- **Definição**: Técnicas que penalizam grandes coeficientes em features para evitar overfitting.
- **Exemplos**: Lasso (L1), Ridge (L2).

---

## 8. Métricas de Avaliação de Modelos

- **Precisão (Accuracy)**: Proporção de previsões corretas.
- **Recall**: Capacidade do modelo de encontrar todas as instâncias relevantes.
- **F1-Score**: Combinação de precisão e recall para conjuntos desbalanceados.
- **AUC-ROC**: Avalia o desempenho do modelo em diferentes limiares de decisão.

**Exemplo**: Comparar essas métricas em um problema de diagnóstico médico para maximizar recall.

---

## Conclusão

Ensinar os fundamentos de Machine Learning de forma detalhada envolve explicar as diferenças entre IA, ML e DL, abordar os tipos de aprendizado supervisionado, não supervisionado e por reforço, além de cobrir o ciclo de desenvolvimento (CRISP-DM), divisão de dados, escolha de algoritmos, e validação de modelos. As métricas e técnicas avançadas, como regularização e validação cruzada, completam a base necessária para a construção de modelos robustos.