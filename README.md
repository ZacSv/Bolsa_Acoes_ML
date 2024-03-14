Este projeto é um modelo baseado em LSTM (Long short-term memory), a finalidade é totalmente educacional, sempre me interessei em modelos de Deep Learning e também na bolsa de valores. <br>
A proposta é treinar o modelo com datas inputadas pelo próprio usuário e a ação a ser analisada também será definida pelo usuário. Após inserir estes dados, o modelo divide o prazo escolhido pelo usuário em duas partes: 80% dos dados para treinamento e 20% para deparar a acertabilidade do modelo. <br>
O modelo é treinado para evoluir a cada iteração com os dados e utilizo o RMSE (erro médio quadrático) para calcular a acertabilidade do modelo.<br>
Por fim o modelo tenta predizer o preço do dia seguinte para a ação. <br>
As bibliotecas utilizadas são:
- Pandas
- Numpy
- Keras
- Yahoo Finance
- Scikit-learn
- Matplotlib <br>
Abaixo segue exemplo do gráfico que o modelo é capaz de gerar durante o treinamento, consegue-se também observar a acertabilidade do modelo, vale lembrar que este gráfico remete ao treinamento.<br>
<img src="https://raw.githubusercontent.com/ZacSv/Bolsa_Acoes_ML/main/exemplo/Graph.png" alt="Texto Alternativo">
