# DataScience_BayesIngenuo

# Naive Bayes

O teorema de Bayes criado por Thomas Bayes no séc. XVIII foi a inspiração para elaboração do algorítimo Naive Bayes, que se tornou um classificador probabilístico
popular na área de Aprendizado de máquina. De acordo com Becker (2019) o algoritmo se tornou popular por ser simples, rápido e possuir um desempenho semelhante a outros classificadores. A principal característica do algoritmo é que ele desconsidera completamente a correlação entre os atributos(características), tratando cada um de forma independente.

## Para definir o teorema de Bayes considere a seguinte notação:

  
  I. *P(h)* como sendo a probabilidade inicial da hipótese antes dos dados serem observados, chamada também de a priori de *h*.

  II. *P(D)* como sendo a probabilidade de observar o resultado *D* na base de dados de treinamento.

  III. *P(D|h)* é a probabilidade de observar os dados de treinamento *D* dado à ocorrência da hipótese *y*, também chamada de probabilidade condicional.

De fato o interesse é em *P(h|D)* que é a probabilidade de observar a hipótese *h* dado que os dados *D* foram obtidos.Esta quantidade é chamada de probabilidade a posteriori de *h*, porque reflete a confiança na hipótese *y*, após observarmos os dados *D*.

O teorema de Bayes provê uma forma de calcular a probabilidade a posteriori *P(h|D)*, dado a priori *P(h)* junto com a condicional *P(D|h)* que foi obtida nos dados de
treinamento. A equação a seguir descreve o classificador de Bayes:


![Bayes Ingênuo](https://github.com/JaneOliveira/DataScience_BayesIngenuo/blob/main/Eq_bayes.png)


A base utilizada para os testes: "HOFMANN, H. . "german credit data". "UCI - Repositório de aprendizado de máquina",2000.
