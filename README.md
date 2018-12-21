# Imbalance data

Em diversas aplicações de algoritmos de classificação podemos nos deparar com o problema de dados de diferente magnitude, ou ainda denominados de "desbalanceados" ou então do original "imbalance data". Isso ocorre quando temos uma classe que contém poucas informações em relação as demais classes, o que acaba influenciando nos algoritmos de decisão para a escolha da classe com mais dados. Felizmente há diversas técnicas que podem ser utilizadas para contornar esse problema, e apresentamos aqui a discussão com base no pacote imbalance-learn do python. <br>
As opções são divididas em diferentes notebooks, mas sempre usando o mesmo conjunto de dados para facilitar a comparação. No geral, podemos resumir os algoritmos de acordo com o objetivo do rebalanceamento da amostra: <br>
1. Under_sampling: <br>
    Usado para extrair uma amostra da classe que possui o maior número de dados e, com isso, deixar sua dimensão próxima a classe com menor número. No pacote "imbalance-learn" estão disponíveis 11 diferentes algoritmos para fazer o under_sampling. <br>
2. Over_sampling:  <br>
    Essa técnica faz o caminho inverso da anterior, qual seja, amplia a amostra da classe com menor número de dados. Aqui podemos usar 5 diferentes algoritmos. <br>
3. Combinando under e over_sampling:   <br>
    Em alguns casos essa opção se mostra mais factível de ser implementada resultando em melhor performance do algoritmo de classificação. Mas isso não é regra, e irá depender da distribuição dos dados. Aqui temos basicamente duas técnicas ligadas ao SMOTE: i) Tomek links e, ii) ENN.  <br>
4. Ensemble: <br>
    Aqui já começamos a fazer uso de um processo mais elaborado para resolver o problema de dados desbalanceados. São vários algoritmos disponíveis, como o random forest e svm, que podem ser usados em uma etapa anterior, com a ajuda do bagging, para produzir amostras que tenham performance mais parecida e, com isso, aplicar o procedimento no passo seguinte na análise de Machine Learning ou Deep Learning.
