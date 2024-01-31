# BibliotecaPandas

#O case abordado é de uma loja de varejo virtual, onde atende todo o território nacional, vendendo vários produtos em departamentos diferentes, além disso a loja conta com diversos canais de vendas como: marketplace, loja física e entre outros.

Premissas de negócios:
Ao analisar os dados deparei com muitos desafios e para isso foi preciso considerar algumas premissas de négocios. A primeira dela é que, devido a um erro no BD, algumas compras não possuem informações da UF (Unidade Federativa). Para solucionar o problema foi decidido que todas as compras com dados nulos (Null) seriam considerados da Unidade Federativa do Mato Grosso do Sul(MS). A segunda é que o preço do produto não pode ser maior do que o preço com frete, então para isso foi feito um ticket médio dos preços para resolver esse tipo de problema.

Métricas:
Com base nas decisões tomadas nas premissas foi adotada as seguintes métricas:
1- Departamento mais vendidos: Analisando os dadis de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação pode ser útil para entender quais são os produtos mais procurados pelos clientes e com base nisso poder desenvolver estratégias de vendas.
2-Média de preços por departamento: analisamos a média de preços por departamento para que possamos entender como cada departamento se comporta e também identificar os departamentos com o ticket médio melhor, podendo assim ajudar nas tomadas de decisões por departamentos e preços médios dos produtos nos departamentos.
3-Quantidade de vendas por mês: Analisando as vendas por mês é possivel identificar sazonalidades no comportamento de cada mês ajudando assim a empresa a tomar futuras decisões de contratações extas e também meses mais propício para férias de funcionários.
4-Média de renda per capta por cada tipo de canal de venda: Auxiliar a equipe de marketing a criações de campanhas para captação de clientes por rendas e canal de vendas.
5-Média de idade por clientes por bandeiras: Auxiliar na escolha de perfis de público alvo.
