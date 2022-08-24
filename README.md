# Modulo_2_P3_Clusterizacao
 Curso Ciência de dados da Blue Edtech - Clusterização_de_dados_de_vendas_de_produtos


# Projeto 3 - Clusterização de dados de vendas de produtos - Wholesale customers Data Set - UCI

## Introdução
   - O conjunto de dados de vendas esta localizado na plataforma UCI no seguinte link - https://archive.ics.uci.edu/ml/datasets/Wholesale+customers. Este é um conjunto de dados que não possui rotulo, o nosso desafio será agrupar essas vendas em grupos e avaliar estes grupos.
Segue a descrição das variaveis:
FRESH: gastos anuais em produtos frescos
MILK: gastos anuais em produtos lácteos
GROCERY: gastos anuais em produtos de mercearia
FROZEN: gastos anuais em produtos congelados
DETERGENTS_PAPER: gastos anuais em detergentes e produtos de papel
DELICATESSEN: gastos anuais em produtos artesanais (queijos, vinhos, doces)
CHANNEL: origem do cliente - Horeca (Hotel/Restaurante/Café) (1) ou canais de varejo (2)
REGION: região do cliente Lisbon (1), Oporto (2) or Other Region (3)
referencia:
Abreu, N. (2011). Analise do perfil do cliente Recheio e desenvolvimento de um sistema promocional. Mestrado em Marketing, ISCTE-IUL, Lisbon
Sobre este projeto
Neste projeto treine os conhecimentos aprendidos até o momento e que entenda algumas das dificuldades que pode ter quando for aplicar os mesmos.
Os principais pontos que serão avaliados:
Levantamento de hipoteses
Manipulação de dados e criação de gráficos simples com o Pandas
Criar um modelo clusterização e justificar
Preparação do ambiente
Acessem o link - https://archive.ics.uci.edu/ml/machine-learning-databases/00292/Wholesale%20customers%20data.csv e faça o download do conjunto de dados.
Exercicio 1. (3.0 pontos)
Faça um gráfico de cotovelo, quantos clusters aproximadamente melhor separam este conjunto de dados informado pelo grafico de cotovelo?
#### VALE 0.5 pontos
#### CONSTRUA OS SEUS GRAFICOS ABAIXO, USE MAIS CELULAS SE NECESSARIO

#.
#.
#.
RESPOSTA (VALE 1.0 ponto): (responda aqui, dê dois cliques para editar. Esta célula de texto esta escrito em Markdown, para renderizar o texto execute a célula com Shift+Enter)
Construa um modelo de clusterização K-Médias usando o melhor numero de clusters informado pelo gráfico de cotovelo e usem o parametro random_state com valor 10.
#### VALE 0.5 pontos
#### EXECUTE OS COMANDOS ABAIXO, USE MAIS CELULAS SE NECESSARIO

#.
#.
#.
Adicione o resultado da clusterização no conjunto de dados original, chame essa nova variavel de cluster e conte quantas observações há em cada cluster e preencha:
#### VALE 0.5 pontos
#### EXECUTE OS COMANDOS ABAIXO, USE MAIS CELULAS SE NECESSARIO

#.
#.
#.
#### VALE 0.5 pontos
# Substitua __ pelos valores solicitados
print('Total de observações do cluster 1: {}'.format('__'))
print('Total de observações do cluster 2: {}'.format('__'))
print('Total de observações do cluster 3: {}'.format('__'))
# copie a linha de cima, alterando o cluster e preenchendo o total
Total de observações do cluster 1: __
Total de observações do cluster 2: __
Total de observações do cluster 3: __
Exercicio 2. (4.0 pontos)
Escolha dois clusters e separe os dados em dois subconjuntos, chamando-os de clusterA e clusterB.
#### VALE 1.0 ponto
#### EXECUTE OS COMANDOS ABAIXO, USE MAIS CELULAS SE NECESSARIO

#.
#.
#.
Utilizaremos a função .describe() para obtermos as medidas de média, desvio padrão, valor minimo e valor máximo dos subconjuntos clusterA e clusterB
#### VALE 1.0 ponto
#### EXECUTE O COMANDO ABAIXO PARA clusterA

#.
#### VALE 1.0 ponto
#### EXECUTE O COMANDO ABAIXO PARA clusterB

#.
Comparando as médias, valores minimos e máximos obtidos, há diferença entre o subconjunto clusterA e clusterB?
RESPOSTA (VALE 0.5 pontos): (responda aqui, dê dois cliques para editar)
Sendo dois agrupamentos distintos, qual rotulo poderiamos utilizar para identifica-los? Justifique a sua resposta
RESPOSTA (VALE 0.5 pontos): (responda aqui, dê dois cliques para editar)
Exercicio 3. (3 pontos)
Responda, quais são as vantagens e desvantagens do algoritmo K-Médias?
RESPOSTA (VALE 1.0 ponto): (responda aqui, dê dois cliques para editar)
Quantos elementos há em cada clusters se o numero de clusters for igual ao total de observações? Se o parametro k for igual a 1, quantos clusters teremos e quantos elementos há em cada cluster?
RESPOSTA (VALE 1.0 ponto): (responda aqui, dê dois cliques para editar)
A inicialização dos centroides afeta o algoritmo K-Médias?
RESPOSTA (VALE 1.0 ponto): (responda aqui, dê dois cliques para editar)
