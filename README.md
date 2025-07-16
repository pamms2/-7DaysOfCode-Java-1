# 🎬 Dia 1 - Top 250 Filmes - Busca via API

Este projeto faz parte do primeiro dia do #7DaysOfCode da Alura, com o tema “filmes”. <br>

O desafio visa o aprendizado prático de como consumir APIs em Java, realizar requisições HTTP e processar as respostas.

## 🔎 Objetivo

O objetivo principal foi consumir a API do IMDb para buscar os 250 filmes mais bem avaliados e imprimir no console, em formato JSON, o retorno dessas consultas.
<br>

## 💻 Resolução

Foi utilizada a OMDb API, que permite consultas públicas a dados de filmes, utilizando uma chave de API gratuita.

### ⚙️ Tecnologias Utilizadas
- VSCode (IDE)
- Java 23
- API OMDb

### 🛠️ Etapas
As etapas foram:
- Criação manual de uma lista com os títulos dos 250 filmes mais bem avaliados;
- Armazenamento da chave da API no arquivo ```apikey.txt``` (que está no ```.gitignore``` para não ser enviado ao repositório);
- Implementação do cliente HTTP usando ```java.net.http.HttpClient```, ```HttpRequest``` e ```Httpresponse```;
- Requisição GET à API, para cada filme da lista, imprimindo o JSON retornado no console.

### ❓ Por que não usei a API do IMDb?
Atualmente, o IMDb oferece acesso aos seus dados completos apenas por meio de uma nova API, que está disponível exclusivamente via AWS Data Exchange, tendo custos elevados. Dessa forma, tornou-se inviável a utilização da API para um projeto de estudo.

## ✅ Conclusão
O projeto permitiu praticar consumo de APIs em Java, trabalhando com requisições HTTP e impressão de dados no console. <br>
Mesmo usando a OMDb como alternativa gratuita ao IMDb, foi possível atender ao objetivo do desafio e preparar a base para evoluções nos próximos dias do #7DaysOfCode.
