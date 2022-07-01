# Preço de vendas de apartamentos - Coreia do Sul

Esté é um trabalho de regressão onde queremos prever o preço dos apartamentos a partir de algumas informções (algumas features).

Depois de preparar o nosso conjunto de dados, aplicamos alguns modelos de machine learning e verificamos suas precisões:

![image](https://user-images.githubusercontent.com/83425571/176974961-07c77fe1-67e9-4fab-86bc-a0e05be5fe0f.png)

Ao análisarmos a figura acima, conseguimos enxergar que o modelo RandomForrestRegressior obteve os melhores resultados, cerca de 98% enquanto que XGBoost e DecisionTree ficaram bem proximos com 97 e 96 %, respectivamente. 

Selecionamos a RFR, fizemos um fit e plotamos os valores previstos e os valores reais, como segue abaixo:

![image](https://user-images.githubusercontent.com/83425571/176975188-50f34c4f-53a0-4e1b-8854-76478aece46f.png)

temos ótimos resultados. 

Agora, pra finalizar, encontramos quais features mais contribuem para o preço dos apartartamentos e plotamos abaixo:

![image](https://user-images.githubusercontent.com/83425571/176975351-e4530839-5bde-4895-a39e-1f17f4092b9b.png)

Os preços dos apartamentos são influenciados por: cerca de 43 % pelo size, 21 % pelo HallwayTipe, 16 % pelo Yr Sold e 5 % pelo YearBuild
