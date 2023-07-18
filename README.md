# Spotify_streamings

O Spotify disponibiliza aos seus usuários dados da própria conta, sendo possível solicitar por aqui:

[Spotify](https://www.spotify.com/br-pt/account/privacy/)

A base de dados aqui utilizada foi solicitada em "Obter seus dados" (Get Your Data) -> Histórico de streaming do ano passado.
Os arquivos foram divididos em 3 no formato JSON e contém informações sobre o histórico de streaming do usuário, incluindo o nome da faixa, o artista, a data e a hora da reprodução.

- A utilização da biblioteca pandas para ler os arquivos JSON e transformá-los em dataframes e concatená-los para uma análise mais precisa;
- Com esses dados, pude descobrir o Top 10 de artistas mais reproduzidos;
- As músicas mais executadas do artista mais ouvido;
- Quantas vezes a mesma música foi executada  e criar um Top15;
- Criar o gráfico que mostra as palavras que mais aparecem nos títulos das músicas. Utilizando a biblioteca WordCloud para gerar a nuvem de palavras, onde cada palavra é representada em tamanho proporcional à sua frequência nos títulos. Quanto maior o tamanho da palavra, mais frequente ela é nos títulos das músicas;
- Contar o número de reproduções em cada mês e plotar um gráfico com essa informação;
- Contar o número de reproduções em cada hora;
- Criar uma coluna com o dia da semana em que cada música foi executada e calcular qual foi o dia da semana com mais reproduções;
- Descobrir o dia com mais execuções e quais bandas foram as mais ouvidas nesse dia em questão;
- Top 10 dos dias com mais músicas executadas;
- Calcular a soma do tempo de reprodução por artista - Top10;
- Somar o total de horas reproduzidas: 1450 em um intervalo de 368 dias 😨;
- E salvar esse dataframe concatenado em um arquivo excel, além de outras abas com informações do Top10 - Artistas, Playlist do artista mais tocada, Músicas mais tocadas, Datas com mais execução e o gráfico WordCloud.
