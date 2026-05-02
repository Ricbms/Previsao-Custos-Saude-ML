# 🏥 Previsão de Custos de Seguro Saúde com Machine Learning

Este projeto explora um dataset de custos hospitalares para identificar os principais fatores que influenciam o valor do seguro e desenvolve um modelo de regressão para prever esses custos.

## 📋 Resumo do Projeto
O objetivo foi analisar dados de pacientes (idade, IMC, tabagismo, etc.) e entender como o estilo de vida impacta financeiramente as seguradoras.

## 🛠️ Tecnologias Utilizadas
- **Python** (Pandas, Numpy)
- **Visualização:** Seaborn e Matplotlib
- **Machine Learning:** Scikit-Learn (Random Forest Regressor)

## 📈 Principais Insights
- **Tabagismo:** É a variável com maior impacto, elevando drasticamente os custos.
- **IMC vs Tabagismo:** Existe uma sinergia negativa; fumantes obesos custam significativamente mais que a soma dos dois fatores isolados.
- **Performance do Modelo:** O Random Forest atingiu um R² de ~86%.

## 🚀 Como executar
1. Clone o repositório.
2. Certifique-se de ter o `scikit-learn` instalado.
3. Execute o notebook `Analise_teste.ipynb`.
