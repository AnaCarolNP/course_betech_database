# Análise Exploratória do Dataset "Disney Plus Movies and TV Shows"

Neste notebook, realizamos uma análise exploratória do dataset "Disney Plus Movies and TV Shows". O objetivo foi obter insights sobre os filmes e programas de TV disponíveis na plataforma Disney Plus.

### ℹ️ Fonte dos Dados
Os dados utilizados foram obtidos a partir do seguinte link: [Dataset Disney Plus Shows on Kaggle](https://www.kaggle.com/datasets/unanimad/disney-plus-shows).

## 🎲 Dados Utilizados
O dataset utilizado contém informações sobre os registros e inclui as seguintes colunas:

- **imdb_id**: Identificador único do filme ou série no IMDb.
- **title**: Título do filme ou série.
- **plot**: Sinopse ou resumo do enredo.
- **type**: Indica se é um filme ou uma série.
- **rated**: Classificação etária atribuída.
- **year**: Ano de lançamento.
- **released_at**: Data de lançamento.
- **added_at**: Data em que foi adicionado ao Disney Plus.
- **runtime**: Duração em minutos.
- **genre**: Gêneros ou categorias aos quais pertence.
- **director**: Diretor responsável pelo filme ou série.
- **writer**: Escritor ou roteirista do filme ou série.
- **actors**: Atores principais envolvidos no filme ou série.
- **language**: Idioma original do filme ou série.
- **country**: País de origem do filme ou série.
- **awards**: Prêmios ou reconhecimentos recebidos.
- **metascore**: Pontuação média do filme ou série no Metacritic.
- **imdb_rating**: Avaliação do filme ou série no IMDb.
- **imdb_votes**: Quantidade de votos no IMDb.

## 📚 Bibliotecas Utilizadas
Durante a análise, foram utilizadas as seguintes bibliotecas:

- **pandas**: Utilizada para manipulação e análise dos dados.
- **pandasql**: Utilizada para executar consultas SQL nos DataFrames do pandas.
- **sqlalchemy**: Utilizada para trabalhar com consultas SQL e o banco de dados.

## ⚙️ Etapas do Notebook

1. Instalação de Bibliotecas e Importação da Base de Dados: Nesta etapa, foram instaladas as bibliotecas necessárias (pandas, pandasql e sqlalchemy) e importado o dataset do Disney Plus Movies and TV Shows utilizando a biblioteca pandas.

2. Análise Descritiva: Realizamos uma análise descritiva dos dados, explorando as informações contidas nas colunas. As análises realizadas incluíram a verificação da tipagem dos dados, a contagem de valores nulos em cada coluna e a contagem de valores únicos nas colunas categóricas.

3. Consultas SQL: Utilizamos a biblioteca pandasql para executar consultas SQL nos dados, obtendo insights sobre os filmes e programas de TV.
