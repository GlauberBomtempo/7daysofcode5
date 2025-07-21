# Análise de Machine Learning - Validação de Modelos 🎶

Este repositório contém a resolução do 5º Desafio do projeto #7DaysOfCode - Machine Learning. O foco principal é avaliar diferentes modelos de classificação para prever a popularidade de músicas no Spotify, utilizando múltiplas métricas de avaliação e validação cruzada.

## 📌 Sobre o Projeto

O projeto contempla as seguintes etapas:

- Pré-processamento completo dos dados;
- Criação da variável binária `popular_binaria` com base na popularidade;
- Criação da variável `artistas_relevantes` baseada nos 5000 artistas mais populares;
- Aplicação de OneHotEncoding nas variáveis categóricas;
- Divisão dos dados em treino, validação e teste;
- Implementação de validação cruzada estratificada (`StratifiedKFold`);
- Treinamento e validação de três modelos de classificação: Árvore de Decisão, Random Forest e XGBoost;
- Avaliação detalhada com métricas de Acurácia, Precisão, Recall e F1-Score;
- Análise comparativa de desempenho entre modelos.

## 📊 Principais Etapas

- 🔎 **Análise Exploratória**: já realizada nos desafios anteriores com gráficos de distribuição, correlação e foco nos 1000 mais populares;
- 🛠️ **Pré-processamento**: eliminação de colunas irrelevantes, criação de novas features, aplicação de OneHotEncoding;
- 🎯 **Balanceamento monitorado**: todas as divisões de dados acompanharam o balanceamento da variável target;
- 🚀 **Validação dos Modelos**:
  - Árvore de Classificação;
  - Random Forest;
  - XGBoost;
- 📈 **Validação cruzada (StratifiedKFold)** com análise das métricas em cada fold e cálculo da média;
- ✅ Comparação das métricas Acurácia, Precisão, Recall e F1-Score entre os modelos.

## 📝 Como executar

1. Clone o repositório:
```bash
git clone [https://github.com/GlauberBomtempo/7daysofcode5/blob/main/7daysofcode5.ipynb]
```
2. Instale as bibliotecas necessárias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
````
3. Execute o notebook 7daysofcode5.ipynb no ambiente de sua preferência.


##📂 Estrutura do Repositório
7daysofcode5.ipynb → Notebook completo da análise do desafio 5;

README.md → Este arquivo de descrição do projeto.

🚩 Conclusão
Este projeto vai além da proposta original do desafio, aplicando práticas robustas de validação e análise comparativa entre modelos, possibilitando maior confiança nos resultados obtidos.

📢 Observação Importante
Este projeto tem finalidade educacional, utilizando dataset público do Spotify via Alura.

📊 Desenvolvido por Gláuber Lopes Bomtempo


   
