# EDA-Youtube-API

<p>Com o intuito de entender melhor o que faz um vídeo ter sucesso na plataforma foi feita uma análise entre os nove canais de data science mais populares do Youtube. Além disso, o projeto serviu como estudo para a obtenção de dados através do consumo da API do Youtube e para análise de dados com a utilização de Python.</p>

### Conclusões
Neste projeto exploramos os dados dos 9 canais mais populares em língua inglesa sobre Data Science/Data Analysis e obtivemos insights interessantes para quem quer criar um canal no YouTube sobre este nicho ou semelhante:

* Quanto mais interações (curtidas e comentários) um vídeo tem, maior o número de visualizações proporcionalmente. Vale dizer que o que se percebe é uma correlação, que, diferente de uma relação causalidade, pode ocorrer nos dois sentidos. Com o fator de correção de interações por mil visualizações, percebemos o efeito de aprovação social das interações, os usuários tendem a interagir com conteúdos com alto número de interações, proporcionalmente.

* A maioria dos vídeos tem entre 5 e 30 tags.

* Os vídeos com maior número de visualizações tendem a ter em média um título contendo entre 30 a 70 caracteres. Vídeos com poucos ou muitos caracteres aparentam sofrer com baixo número de visualizações.

* Normalmente os vídeos são publicados nas Segundas e Sextas. O final de semana, particularmente, tem menos publicações de conteúdo.

* Os termos chaves dos comentários são relativamente positivos. Foi interessante notar o alto uso da palavra "please", sugerindo um potencial de conteúdo não explorado.

### Limitações do projeto
Os insights obtidos deste projeto devem levar em conta alguns fatores:

* O número de vídeos é relativamente pequeno (o dataset tem menos de 4,3 mil registros).

* Por limitação da API do Youtube, só foi possível obter a íntegra de 10 comentários por vídeo, ou seja, a nuvem de palavras pode não refletir a totalidade dos comentários.

* Existes muitos fatores que não puderam ser levados em conta durante a análise, como a estratégia de marketing de cada criador de conteúdo e muitos efeitos aleatórios que podem afetar o sucesso de um vídeo.
Ideia para um futuro projeto

### Para expandir a análise dos dados podemos:

* Expandir a análise para canais com menos relevância no nicho de ciência de dados.

* Fazer uma análise de sentimento com os comentários e encontrar quais vídeos tem mais e menos comentários positivos.

* Fazer uma análise das perguntas feitas nos comentários para encontrar lacunas nos conteúdos dos criados.

* Aplicar a análise em outros nichos(vlogs ou canais de games) e fazer uma comparação dos resultados, identificando padrões que independem do tipo de conteúdo dos vídeos.

<a href='https://github.com/Ribeiro-Pedro/EDA-Youtube-API/blob/main/youtube_api.ipynb'>Link do notebook</a>
