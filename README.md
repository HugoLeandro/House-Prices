# House Prices Kaggle
Técnicas Avançadas de Regressão
Repositório criado para a **[competição do Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) sobre a previsão de preço das casas** na cidade de Ames, Iowa (Estados Unidos)


<img src="https://github.com/HugoLeandro/House-Prices/blob/main/Imagens/kaggle_5407_media_housesbanner.png" width=800/>


## [Etapa 1: Primeiro Modelo](https://github.com/HugoLeandro/House-Prices/blob/main/Etapa1.ipynb)
- Nesta etapa, realizei uma abordagem inicial simples, sem aplicar tratamento ou engenharia de dados. O objetivo foi observar os resultados de forma direta.
- Para simplificar, **preenchi todos os valores ausentes com -1** e **removi todas as colunas de dados textuais.**
- Criei modelos utilizando três algoritmos: **3 algoritmos**: **[Regressão Linear](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)**, **[Árvore de Regressão](https://scikit-learn.org/stable/modules/tree.html#regression)** e **[KNeighborsRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html#sklearn.neighbors.KNeighborsRegressor)** e **A avaliação dos resultados foi feita com base no**  **[Erro Médio Absoluto](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)** e no  **[Erro Quadrático Médio](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html)**,priorizando o último, conforme o critério da competição.
- O **score público retornado pelo Kaggle foi: 0,25476.**

- Resultado obitido:
<img src="https://github.com/HugoLeandro/House-Prices/blob/main/Imagens/resultado-kaggle1.png"/>
