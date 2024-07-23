<h1> <b>NBA Hall of Fame Prediction</b> </h1> 
<h2>Overview</h2>
<p>Este projeto utiliza BeautifulSoup para coletar dados de jogadores da NBA, pandas para modelagem de dados, e scikit-learn para prever quais jogadores têm maior probabilidade de serem introduzidos no Hall of Fame da NBA.</p>

<h2>Table of Contents</h2>
<ul>Project Description</ul>
<ul>Data Collection</ul>
<ul>Data Modeling</ul>
<ul>Acknowledgements</ul>

<h2>Project Description</h2>
<p>Este projeto tem como objetivo prever a probabilidade de jogadores da NBA serem introduzidos no Hall of Fame. Utilizamos dados históricos de desempenho de jogadores e características para treinar um modelo de aprendizado de máquina que faz essas previsões.</p>

<h2>Data Collection</h2>
<p>Os dados dos jogadores da NBA são coletados utilizando BeautifulSoup para fazer web scraping de sites de estatísticas de basquete.</p>

<h2>Data Features</h2>

<ul>Nome do Jogador: Nome completo do jogador.</ul>
<ul>Número de jogos: Número de jogos que o jogador jogou.</ul>
<ul>Minutos Jogados: Minutos jogados pelo jogador ao longo da carreira.</ul>
<ul>Field Goals Tentados: Número total de arremessos de campo tentados.</ul>
<ul>Field Goals Acertados: Número total de arremessos de campo acertados.</ul>
<ul>Porcentagem de Field Goal: Percentual de acertos nos arremessos de campo.</ul>
<ul>Field Goals de 3 Pontos Tentados: Número total de arremessos de 3 pontos tentados.</ul>
<ul>Field Goals de 3 Pontos Acertados: Número total de arremessos de 3 pontos acertados.</ul>
<ul>Porcentagem de Field Goal de 3 Pontos: Percentual de acertos nos arremessos de 3 pontos.</ul>
<ul>Lances Livres Feitos: Número total de lances livres feitos.</ul>
<ul>Lances Livres Tentados: Número total de lances livres tentados.</ul>
<ul>Porcentagem de Lances Livres: Percentual de acertos nos lances livres.</ul>
<ul>Rebotes Ofensivos: Número total de rebotes ofensivos.</ul>
<ul>Rebotes Defensivos: Número total de rebotes defensivos.</ul>
<ul>Rebotes Totais: Número total de rebotes.</ul>
<ul>Assistências: Número total de assistências.</ul>
<ul>Roubos de Bola: Número total de roubos de bola.</ul>
<ul>Tocos: Número total de tocos.</ul>
<ul>Turnovers: Número total de turnovers.</ul>
<ul>Faltas Pessoais: Número total de faltas pessoais.</ul>
<ul>Pontos: Número total de pontos.</ul>
<ul>Assistências por Turnover: Média de assistências por turnover.</ul>
<ul>Roubos de Bola por Turnover: Média de roubos de bola por turnover.</ul>
<ul>Eficiência: Medida de eficiência do jogador (pode variar dependendo da fórmula utilizada).</ul>
<ul>True Shooting Percentage: Percentual de arremessos verdadeiros, que leva em conta field goals, 3 pontos e lances livres.</ul>
<ul>Pontos por Jogo: Média de pontos por jogo ao longo da carreira.</ul>
<ul>Assistências por Jogo: Média de assistências por jogo ao longo da carreira.</ul>
<ul>Rebotes por Jogo: Média de rebotes por jogo ao longo da carreira.</ul>
<ul>Anos de Carreira: Número total de anos jogados na NBA.</ul>
<ul>Outros atributos estatísticos relevantes.</ul>

<h2>Data Modeling</h2>
<p>Os dados coletados são processados e modelados utilizando pandas. As seguintes etapas são realizadas:</p>

<ul>Limpeza e tratamento de dados.</ul>
<ul>Análise exploratória de dados (EDA).</ul>
<ul>Engenharia de características (feature engineering).</ul>
<h2>Prediction</h2>
<p>Um modelo de aprendizado de máquina é treinado utilizando scikit-learn para prever a probabilidade de um jogador ser introduzido no Hall of Fame. Os seguintes algoritmos são utilizados:</p>

<ul>Random Forest</ul>
<ul>Gradient Boosting Classification</ul>
<ul>Regressão Logística</ul>
<ul>Multi Layer Perceptron</ul>

<h2>Acknowledgements</h2>
<ul><a href =https://beautiful-soup-4.readthedocs.io/en/latest/>BeautifulSoup</a></ul>
<ul><a href =https://pandas.pydata.org/docs/>pandas</a></ul>
<ul><a href =https://scikit-learn.org/stable/ >scikit-learn</a></ul>
<h2>Data source</h2>
<ul><a href = https://www.nba.com/stats>NBA stats</a></ul>

