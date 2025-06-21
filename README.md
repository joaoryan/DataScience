# 📊 Análise do Mercado Bovino Brasileiro (2020-2025)

Projeto de Machine Learning para análise de exportações e preços do gado bovino no Brasil, integrando dados econômicos e predição de tendências.

## 🎯 Objetivos

1. **Análise de Mercado**:
   - Identificar padrões nas exportações de produtos bovinos (carne, animais vivos, subprodutos)
   - Mapear estados brasileiros com maior volume de exportação

2. **Modelagem Preditiva**:
   - Prever variações no preço do boi gordo usando:
     - Dados históricos de preços
     - Indicadores econômicos (IPCA/inflação)
   - Comparar desempenho de modelos (Random Forest vs ARIMA)

3. **Geração de Insights**:
   - Correlação entre inflação e preço do boi
   - Sazonalidade e volatilidade do mercado
   - Recomendações estratégicas para o setor


## ⚙️ Tecnologias Utilizadas

- **Python 3.9+**
- Bibliotecas:
  - `pandas` | `numpy` (análise de dados)
  - `matplotlib` | `seaborn` (visualização)
  - `scikit-learn` (Random Forest)
  - `statsmodels` (ARIMA/STL)
  - `shap` (explicabilidade de modelos)

## 🔍 Principais Resultados

1. **Exportações**:
   - Crescimento médio de **X%** ao ano
   - Estado líder: **MG** (XX% do total exportado)

2. **Preços**:
   - Correlação com IPCA: **0.XX**
   - Melhor mês para compra: **Julho** (preço XX% abaixo da média)

3. **Modelos**:
   | Modelo          | RMSE  | R²    |
   |-----------------|-------|-------|
   | Random Forest   | 12.34 | 0.89  |
   | ARIMA(1,1,1)    | 15.67 | 0.82  |
   | Baseline        | 20.11 | 0.00  |

## 📂 Estrutura do Projeto

```bash
datasetExport/
│   ├── EXP_2020.csv
│   ├── EXP_2021.csv
│   ├── EXP_2022.csv
│   ├── EXP_2023.csv
│   ├── EXP_2024.csv
│   └── EXP_2025.csv  
├── dataset_unificado.csv
├── exportacao_bovino_simplificado.csv
├── Live Cattle Futures Historical Data.csv
├── NCM.csv
└── projeto.ipynb
```

## 👨‍💻 Autor

**João Ryan dos Santos**  

- 💼 [LinkedIn](https://www.linkedin.com/in/joaoryan)  
- 🧑‍💻 [GitHub](https://github.com/joaoryan)