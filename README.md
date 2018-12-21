# Imbalance data

Em diversas aplicações de algoritmos de classificação podemos nos deparar com o problema de dados de diferente magnitude, ou ainda denominados de "desbalanceados" ou então do original "imbalance data". Isso ocorre quando temos uma classe que contém poucas informações em relação as demais classes, o que acaba influenciando nos algoritmos de decisão para a escolha da classe com mais dados. Felizmente há diversas técnicas que podem ser utilizadas para contornar esse problema, e apresentamos aqui a discussão com base no pacote imbalance-learn do python. <br>
As opções são divididas em diferentes notebooks, mas sempre usando o mesmo conjunto de dados para facilitar a comparação. No geral, podemos resumir os algoritmos de acordo com o objetivo do rebalanceamento da amostra: <br>
1. Under_sampling: 
    Usado para extrair uma amostra da classe que possui o maior número de dados e, com isso, deixar sua dimensão próxima a classe com menor número. No pacote "imbalance-learn" estão disponíveis 11 diferentes algoritmos para fazer o under_sampling. <br>
2. Over_sampling:
3. 
