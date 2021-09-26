# Projeto-1-CDados

- Projeto colaborativo de Ciência de Dados para a construção de um Classificador Naive-Bayes, produzido por André Barboza de Braga Melo e Rodrigo Anciães Patelli

- Para que esse projeto fosse feito, foi nescessária a criação de contas student no twitter, estas que são: @RonaldrigoAP

- o arquivo Projeto1_Layout_Classificador.ipynb foi usado inicialmente no projeto mas, posteriormente, passamos a utilizar o Projeto1_Funções_dos_classificadores.ipynb para escrever todo o código. Portanto, é o segundo arquivo que contém todo o código relevante.

- Desenvolvimento do projeto: A primeira etapa foi a ciração das contas de desenvolvedor no Twitter. Com as duas contas obtidas, realizou-se independetemente duas coletas de dados teste com temas distintos. Então, decidiu-se um dos produtos como definitivo do projeto, no caso, "League of Legends". Inicialmente, antes de classificarmos as mensagens manualmente, pensamos que as 500 mensagens mínimas deveriam estar na planilha de treinamento, então aumentamos em 200 o número de tweets dessa planilha. Então, classificamos manualmente - com o critério "é opinativo"(1) ou não é opinativo (0)- e removemos toda a pontuação do texto. Com isso podemos criar o classificador Naive-Bayes de fato. O classificador é baseado na frequência das palavras em cada uma das categorias de tweets. O próximo passo foi verificar o desempenho do classificador na base de dados de teste. Por fim, para gerar uma conclusão a partir de uma quantidade razoável de dados, usamos o classificador para classificar a planilha Treinamento 100 vezes. E a partir disso, obtemos que o nosso classificador tem uma porcentagem de acerto de 70% em média.
