# Projeto de coleta de dados do Valorant

Este projeto tem como objetivo coletar informações do jogo Valorant para análise e visualização de dados.

![image](https://user-images.githubusercontent.com/84351648/235402141-db27a978-d08a-4a7a-802c-4165e6ce8c47.png)

## Ferramentas utilizadas:
- Google Colab: Ambiente de desenvolvimento utilizado para execução do código em Python.
- Beautiful Soup: Biblioteca utilizada para extrair as informações dos sites relevantes.
- Pandas: Biblioteca utilizada para converter os dados obtidos em um data frame e converter em CSV.
- Power BI: Ferramenta utilizada para análise e visualização dos dados coletados.

## Coleta de dados
Para coletar os dados, foram utilizados scripts Python no Google Colab para extrair informações do site tracker.gg usando a biblioteca Beautiful Soup. Foram extraídos dados como:

- Informações dos jogadores, como nome de usuário, rank e horas jogadas;
- Estatísticas das partidas, como número de vitórias, derrotas, eliminações e assistências.

Os dados extraídos foram armazenados em arquivos CSV para facilitar o processo de análise posterior.

## Análise e visualização
Os dados coletados foram analisados e visualizados usando o Power BI. Foram criados gráficos e visualizações para ajudar a extrair insights dos dados, como:

- Gráfico de barras para comparar o desempenho de diferentes jogadores;
- Cards com dados para mostrar números totais e médias de algumas estatísticas.

## Dificuldades
Durante o processo de coleta de dados, foi necessário lidar com algumas dificuldades, como:

- Sites com conteúdo dinâmico que exigiam o uso de técnicas avançadas de raspagem de dados;
- A criação de uma ordem cronológica na extração das informações, que foi resolvida com a criação de tabelas separadas por data;

Essas dificuldades foram superadas com a ajuda de tutoriais online e fóruns de discussão.

## Créditos
Este projeto foi desenvolvido com a ajuda de diversos recursos, como:

- Documentação do Beautiful Soup e Pandas;
- Conhecimentos em Python, estatística e análise de dados;
- Meu conhecimento em Power BI da Microsoft.

## Como executar o código
Para executar o código deste projeto, é necessário abrir o arquivo Jupyter Notebook no Google Colab e executar as células do código na ordem correta. É necessário ter uma conta ativa no Valorant para coletar os dados.

## Contribuições
Contribuições são bem-vindas neste projeto. Se você tiver sugestões ou encontrar algum problema, abra uma nova issue neste repositório ou envie um pull request com suas alterações.
