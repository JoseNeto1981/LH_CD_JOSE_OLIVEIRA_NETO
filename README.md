# LH_CD_JOSE_OLIVEIRA_NETO  
# DESAFIO INDICIUM LIGHTHOUSE - DESAFIO DE CIÊNCIA DE DADOS - IMDB


Este repositório contém a resolução do desafio de Ciência de Dados, envolvendo:
- Análises estatísticas e EDA (Exploratory Data Analysis).
- Criação e treinamento de modelo preditivo.
- Salvamento do modelo final em formato `.pkl`.

## 📂 Estrutura do Repositório
´´´
├── desafio_indicium_imdb.csv # Base de dados utilizada
├── eda_modelagem.ipynb # Notebook com análise, EDA e modelagem
├── models/
│ └── modelo.pkl # Modelo treinado salvo
├── requirements.txt # Dependências do projeto
└── README.md # Documentação do repositório
´´´

## ⚙️ Como executar o projeto

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/JoseNeto1981/LH_CD_JOSE_OLIVEIRA_NETO.git
   cd LH_CD_JOSE_OLIVEIRA_NETO


## Criar um ambiente virtual:
python -m venv venv
venv\Scripts\activate      # Windows


## Instalar dependências:
pip install -r requirements.txt

## Abrir o notebook:
jupyter notebook - comando utilizado dentro do pycharm

## Principais dependências:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

## 🎯 Motivo do Desafio
O objetivo deste desafio foi aplicar na prática conceitos de **Ciência de Dados**, desde a análise exploratória até a construção de um modelo preditivo.  
A ideia central é demonstrar a capacidade de transformar uma base de dados bruta (IMDB) em **insights relevantes** e um **modelo treinado**, seguindo boas práticas de análise e documentação.

---

## 🧩 Metodologia Utilizada
A resolução do desafio foi estruturada em etapas:

1. **Exploração dos Dados (EDA)**  
   - Análise inicial da base (`desafio_indicium_imbd.csv`), verificando tipos de variáveis, valores ausentes e estatísticas descritivas.  
   - Visualização gráfica de distribuições, correlações e padrões relevantes.  

2. **Pré-processamento**  
   - Limpeza e tratamento de valores faltantes.  
   - Normalização e codificação de variáveis, quando necessário.  

3. **Modelagem**  
   - Teste de diferentes algoritmos de machine learning (ex.: Regressão Linear, Árvores de Decisão, Random Forest).  
   - Seleção do modelo com melhor desempenho baseado em métricas de avaliação adequadas (ex.: RMSE, R², acurácia).  

4. **Validação**  
   - Divisão treino/teste para medir generalização do modelo.  
   - Ajuste de hiperparâmetros, quando necessário.  

5. **Persistência do Modelo**  
   - O modelo final foi salvo em `models/modelo.pkl` usando `joblib`, permitindo reuso em aplicações futuras.  

---

## 📑 Relatórios
- Todas as análises estatísticas e o EDA estão documentados no notebook [`untiled2.ipynb`](untiled2.ipynb).
- Também disponibilizado em [`desafio_indicium_imdb.pdf`](desafio_indicium_imdb.pdf) para facilitar a visualização em formato de relatório.
- O modelo final foi salvo em [`models/modelo.pkl`](models/modelo.pkl).


## ✅ Considerações Finais
- O desafio cumpriu seu papel ao mostrar o fluxo completo de um projeto de Ciência de Dados: **da exploração ao produto final (modelo salvo)**.  
- Durante o processo, foi possível identificar **fatores determinantes** para as variáveis-alvo e avaliar a qualidade do modelo.  
- A organização do repositório foi feita para facilitar a reprodutibilidade, contendo:
  - Base de dados utilizada.  
  - Notebook com análises e código.  
  - Modelo treinado salvo.  
  - Documentação (README).  

Este projeto reforça a importância de uma abordagem estruturada e bem documentada em Ciência de Dados, onde cada etapa contribui para a confiabilidade e aplicabilidade do resultado final.


   
