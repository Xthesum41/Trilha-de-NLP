# Trilha-de-NLP
# 01 - Expressões regulares - REGEX
2	 - Crie um tokenizador utilizando regex que retorne apenas palavras.	
	
3	 - Crie uma expressão regular para extrair CPF e CNPJ de textos.	
	
4	 - Crie uma expressão regular para extrair links de textos e paginas html.	
	
5	 - Crie uma expressão regular para extrair números de telefone de textos.	
	
6	 - É possivel criar um classificador de sentimento rudimentar com regex (resposta positiva/negativa). Crie uma expressões regulares que identifiquem se uma determinada resposta foi positiva ou negativa.	
	
# 02 - Normalização Textual
7	 - Crie um algoritmo de tokenização. (preste atenção a pontuação)	
	
8	 - Crie um algoritmo que realize a segmentação de sentenças.	
	
9	 - Quais são os algoritmos de stemming mais conhecidos?	
	
10 -	Implemente um algoritmo de stemming de sua escolha. (RSLP para portugues)	
	
11 -	Qual é a diferença entre stemming e lemmatization?	
	
12 -	Quais recursos linguisticos o lemmatization utiliza?	
	
13 -	Você enxerga beneficios na utilização do lemmatization ao invés do stemming? Quais?	
	
14 -	Utilize o NLTK para tokenizar os textos e remova as stopwords.	
	
15 -	Utilize o spacy para tokenizar os textos e remova as stopwords.	
	
16 -	Compare o NLTK vs spacy, para quais aplicações cada ferramenta é mais adequada?	
	
17 -	Crie um pipeline de normalização com os algoritmos que VOCÊ implementou.	
	
18 -	Crie um pipeline de normalização na ferramenta de sua escolha.	
	
19 -	Implemente uma função para obter n-gramas de um texto.	
	
# 03 - N-Grams
20 -	Utilize uma biblioteca em python que faça a extração de n-gramas e compare o resultado com a sua função.	
	
21 -	Crie um bag-of-words (contagem de palavras) de um dataset de sua escolha. Utilize os dois pipelines que você criou e compare os resultados.	
	
22 -	Crie um grafico da curva de zipf dos dados antes e depois de executar o pipeline de normalização. Analise os resultados, a que conclusão você chega?	
	
23 -	Você acha que deveriamos cortar palavras do nosso BoW? Justifique a sua resposta.	
	
24 -	Crie novamente o BoW adicionando bigramas e trigramas.	
	
25 -	Ao analisar o gráfico novamente com essa alteração, o que você percebeu de diferente? Alguma keyword surgiu?	
	
26 -	Implemente o algoritmo do TF-IDF.	

#	04 - Representação Textual e Embeddings
27 -	Refaça o cálculo dos pesos das palavras com o TF-IDF (que você implementou). O que mudou? Na sua opinião está refletindo a realidade? Está mais coerente?	
	
28 -	Utilize o sklearn para calcular o TF-IDF.	
	
29 -	Em que tipo de problema a contagem de palavras traria melhores resultados que o TF-IDF?	
	
30 -	Implemente o algoritmo de levenshtein. Que problemas podemos abordar com ele?	
	
31 -	Crie um corretor de palavras utilizando o algoritmo de levensthein. (você precisará de uma base de palavras)	
	
32 -	Treine um modelo de Word2Vec para a mesma base utilizada anteriormente utilizando o gensim.	
	
33 -	Crie um gráfico de duas dimensões para representar o modelo de word embeddings que você criou.	
	
34 -	A partir do modelo que você treinou, imprima as 100 palavras mais similares  e menos similares (positivas e negativas) a uma palavra de sua escolha. As palavras retornadas, fazem sentido? Se não, o que deve ser feito?	
	
35 -	Utilizando o gensim, carregue um modelo pre-treinado e compare os resultados do seu modelo com o modelo pré-treinado.	
	
36 -	Qual é a principal diferença entre o TF-IDF e o word2vec?	
	
37 -	E qual é a diferença entre o word2vec e o fasttext?	
	
38 -	Para qual tipo de problema o fasttext seria mais adequado?	
	
39 -	O que envolve a classificação textual? Cite exemplos de aplicações.	

#	05 - Classificação Textual
40 -	Implemente o algoritmo de Naive bayes.	
	
41 -	Selecione uma base de polaridade textual (negativo e positivo), e realize a classificação quando a polaridade do texto utilizando a algoritmo que você implementou. Quais features você selecionará para realizar a classificação? (lembre-se que existem dicionários que possuem a polaridade de cada palavra)	
	
42 -	Avalie os resultados do seu modelo em relação a outros que utilizaram a mesma base? Quais foram os valores de F1, precision, recall e acurácia?	
	
43 -	Realize a mesma classificação utilizando o algoritmo de Naive bayes do sklearn. Compare os resultados. Estão parecidos?	
	
44 -	Por que você acha que o algoritmo de Naive bayes funciona bem para esse tipo de problema? Para que tipo de problema você acha que ele teria um resultado ruim?	
	
45 -	Utilizando as mesmas features treine outros modelos utilizando o sklearn (Linear regression, SVM, Decision Tree, etc).	
	
46 -	Compare o resultado de todos os modelos treinados.	
	
47 -	Utilize uma base de dados textuais que contenha opiniões de pessoas sobre filmes (IMDB), e construa um classificador de sentimentos.	
	
48 -	O classificador de sentimentos que você construiu, melhora ou piora removendo as stopwords? Se melhorou, por que você acha que isso aconteceu?	
	
49 -	Utilizando LDA, crie um modelo de tópicos utilizando uma base de dados de filmes (sinopses).	
	
50 -	Avalie a qualidade dos tópicos gerados. Qual métrica você utilizou? Por que ela é a mais adequada?	
	
51 -	Utilize um método automático para rotular os tópicos gerados. Os rótulos ficaram coerentes com os tópicos?	
	
52 -	Utilizando o classificador de sentimentos gerado e o modelo de tópicos, crie um sistema de recomendação de filmes, caso o usuário tenha gostado do filme, recomende um similar.	
	
53 -	O seu sistema de recomendação está coerente? O que você faria para melhorar? Utilizando word embeddings melhoraria?	
	
54 -	Qual é a principal diferença entre um chatbot baseado em regras e um baseado em IA?	

#	06 - Chatbots
55 -	Crie um chatbot baseado em regras para uma pizzaria, o chatbot deve fazer a saudação, coletar o pedido e as informações de entrega. Em seguida o chabot confirma o pedido e se despede do usuário.	
	
56 -	O seu chatbot conseguiu atender os clientes da pizzaria? O que acontece se os usuários não falam exatamente o que você programou o chatbot para fazer?	
	
57 -	Crie um modelo de classificação de intenções. As possiveis frases de dialogo serão as instancias de treinamento, e os rótulos os assuntos dessas frases (o cliente da pizzaria pode apenas dar um elogio, pode fazer uma saudação, pedir informação sobre a pizza). Como ficou a qualidade desse classificador? Qual algoritmo você utilizou para treinar? Que features você está utilizando?	
	
58 -	Utilizando o classificador de intents, modifique o chatbot atende de pizzaria, para que ele saiba reconhecer a intenção que o usuário está falando, e a partir dai continuar a conversa.	
	
