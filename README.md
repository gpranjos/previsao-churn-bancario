# Previsão de Churn Bancário com Machine Learning

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

## Descrição do Projeto
Este projeto visa identificar clientes com alto potencial de cancelamento de conta (Churn) em uma instituição financeira, permitindo a implementação de estratégias preventivas de retenção. O custo de reter um cliente é significativamente menor do que adquirir um novo (CAC), tornando este modelo uma ferramenta vital para a saúde financeira do banco.

## Destaques Técnicos e Resultados
* **Acurácia do Modelo:** 87% utilizando o algoritmo **Random Forest**.
* **Feature Engineering:** Criação de categorias de idade que revelaram um insight crítico: clientes entre **46-60 anos** possuem uma taxa de saída superior a 50%.
* **Fatores Decisivos:** Através da análise de correlação e importância de variáveis, identificamos que **Idade**, **Saldo Bancário** e **Nível de Atividade** são os principais indicadores de churn.
* **Matriz de Confusão:** O modelo apresentou alta performance na identificação de clientes que permanecem (1.550 acertos) e identificou com sucesso 183 casos reais de churn.



## Tecnologias Utilizadas
* **Linguagem:** Python.
* **Bibliotecas:** Pandas, Scikit-Learn, Seaborn e Matplotlib.
* **Ferramenta:** Jupyter Notebook.
* **Dados:** Extração automática via **API do Kaggle**.

## Estrutura do Repositório
* `data/`: Pasta contendo o dataset (gerada via API).
* `Previsao_Churn.ipynb`: Notebook com todo o ciclo de ciência de dados (EDA, Limpeza, Engenharia de Variáveis e Modelagem).
* `README.md`: Documentação do projeto.

## Como Reproduzir
1. Certifique-se de ter as bibliotecas instaladas: `pip install kaggle pandas scikit-learn seaborn`.
2. Configure seu `kaggle.json` com suas credenciais de API.
3. Execute o notebook. O download dos dados ocorrerá automaticamente via script.

---
**Autor:** [Seu Nome]
**Contato:** [Seu LinkedIn/E-mail]
