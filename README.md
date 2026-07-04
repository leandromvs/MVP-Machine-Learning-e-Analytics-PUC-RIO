# MVP-Machine-Learning-e-Analytics-PUC-RIO
---

## 📌 Descrição

Este projeto é uma evolução do [MVP de Análise de Dados e Boas Práticas](https://github.com/leandromvs/MVP-Analise-de-dados-e-boas-praticas-PUC-RIO/blob/main/MVP_Analise_de_dados_e_boas_praticas_PUC_RIO_FINAL.ipynb), no qual foram realizadas as etapas de pré-processamento, análise exploratória dos dados (EDA) e a construção de um modelo para previsão das vendas do varejo brasileiro utilizando variáveis macroeconômicas. Nesta etapa, o estudo amplia essa abordagem ao incluir o Índice de Confiança do Consumidor (ICC) e concentrar a análise em dois segmentos com perfis distintos: Artigos farmacêuticos, médicos, ortopédicos, de perfumaria e cosméticos, de caráter predominantemente essencial, e Móveis e Eletrodomésticos, representando o consumo discricionário. Além de prever as vendas desses setores, o projeto busca analisar como fatores como taxa de juros, inflação, desemprego e confiança do consumidor influenciam categorias de consumo com diferentes níveis de essencialidade.

---

## 🎯 Objetivo

O objetivo principal é responder às seguintes questões:

* É possível prever a variação das vendas dos setor de varejo farmacêutico (farmácias) utilizando variáveis macroeconômicas e socioeconômicas?

* É possível prever a variação das vendas dos setor de Eletrodomesticos utilizando variáveis macroeconômicas e socioeconômicas?

* O Índice de Confiança do Consumidor (ICC) contribui para melhorar o desempenho preditivo dos modelos em relação ao uso exclusivo de indicadores macroeconômicos do estudo da sprint anterior?

* Os fatores que mais influenciam as vendas diferem entre os setores analisados, refletindo características distintas de consumo?

* O setor farmacêutico, por possuir características essenciais, apresenta menor sensibilidade a variações econômicas quando comparado ao setor discricionário?

*  Regiões com diferentes níveis de desigualdade de renda (Índice de Gini) respondem de forma distinta às variações dos indicadores macroeconômicos?

*  O ICC apresenta maior relevância para a previsão das vendas do setor discricionário (Eletrodomésticos) do que para o setor farmacêutico, devido à maior influência da confiança e da intenção de compra sobre bens não essenciais?

---

## 📊 Dados Utilizados

O projeto utiliza a base analítica construída no MVP anterior, composta por dados provenientes de fontes públicas oficiais:

* **IBGE / SIDRA**

  * Pesquisa Mensal do Comércio (PMC)
  * Índice de Gini

* **Banco Central do Brasil**

  * Taxa Selic
  * Cotação do Dólar

* **IBGE / PNAD Contínua**

  * Taxa de Desocupação

* **FGV**

  * Índice de Confiança do Consumidor (ICC)

---

## ⚙️ O que foi desenvolvido

* EDA
* Separação entre conjuntos de treino e teste;
* Treinamento de modelos de regressão supervisionada;
* Comparação do desempenho entre diferentes algoritmos;
* Avaliação utilizando métricas de regressão;
* Análise da importância das variáveis (Feature Importance);
* Interpretação dos resultados e validação das hipóteses propostas.

---

## 🤖 Técnicas de Machine Learning Aplicadas

* Regressão Linear (Baseline)
* Random Forest Regressor
* XGBoost Regressor
* Comparação entre modelos
* Avaliação por métricas estatísticas
* Interpretação dos modelos e análise das variáveis mais relevantes

---

## 📊 Avaliação dos Modelos

Os modelos são avaliados por meio de métricas apropriadas para problemas de regressão, como:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² (Coeficiente de Determinação)

Também são analisados:

* Capacidade de generalização;
* Comparação entre modelos;
* Importância das variáveis explicativas;
* Interpretação dos resultados obtidos.

---

## ✅ Observações Importantes

* Este projeto utiliza como base a tabela analítica desenvolvida no MVP anterior.
* Os notebooks possuem comentários detalhados explicando todas as etapas do processo.
* O foco está na construção de um pipeline reprodutível de Machine Learning.
* Foram comparados diferentes algoritmos para identificar o modelo mais adequado ao problema.
* A interpretação dos resultados busca não apenas maximizar a acurácia, mas também compreender os fatores econômicos que influenciam o comportamento das vendas.

---

## 📈 Principais Resultados Esperados

* Identificação das variáveis com maior poder explicativo sobre as vendas;
* Comparação do desempenho entre diferentes algoritmos de regressão;
* Avaliação das diferenças entre setores essenciais e discricionários;
* Análise da influência de fatores macroeconômicos sobre o consumo;
* Validação das hipóteses propostas para o estudo.

---

## 🚀 Próximos Passos

* Explorar modelos específicos para séries temporais;
* Avaliar técnicas avançadas de engenharia de atributos;
* Incorporar novas variáveis econômicas e comportamentais;
* Expandir o estudo para outros segmentos do varejo brasileiro;
* Investigar modelos de Deep Learning para previsão de séries temporais.

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* LightGBM (quando aplicável)
* APIs públicas (IBGE, Banco Central e FGV)

---

## 👨‍💻 Autor

**Leandro Maldonado Vieira dos Santos**
