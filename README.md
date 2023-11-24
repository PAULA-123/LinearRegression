
<h1  align="center"> Regresssão Linear </h1>

  

A **regressão linear** procura relacionamentos lineares entre as observações. Em outras palavras, você precisa encontrar uma função que mapeie suficientemente bem alguns recursos ou variáveis ​​para outros, $f(x_1, ..., x_n)= \beta_0 + \beta_1x_1 + ⋯ + \beta_nx_n$.

  

Os recursos dependentes são chamados de **variáveis ​​dependentes** (trataremos por $y_i$). Os recursos independentes são chamados de **variáveis ​​independentes** (trataremos por $\beta_0, ..., \beta_n$).

  

Os problemas de regressão geralmente têm uma variável dependente contínua e ilimitada. As variáveis independentes , no entanto, podem ser dados contínuos, discretos ou mesmo categóricos.

  

As diferenças $\varepsilon_i = y_i - f(x_i)$ para todas as observações $i = 1, …, 𝑛$, são chamadas de **resíduos** . A regressão trata de determinar os melhores coeficientes previstos – isto é, os coeficientes correspondentes aos menores resíduos.

  <h2  align="center"> Previsão de preços de passagens aérea </h2>

Vamos aplicar as técnicas conhecidas de Regressão Linear para a previsão de preços nas passagens aéreas, utilizaremos a regressão linear múltipla através da função "LinearRegression" da biblioteca ScikitLearn, além da implementação do método Moore-Penrose com pseudo inversa através dos métodos de numpy.

##  

</div>

<p><strong> Dado: </strong> <a  href="https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction">https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction</a></p>

  
  

**Autoria:**

* [Mariana Fernandes Rocha](https://github.com/marimarifr)

* [Paula Eduarda de Lima](https://github.com/PAULA-123)