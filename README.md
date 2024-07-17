# Recomendador de Músicas

## Disclaimer
Criando um recomendador de músicas com um dataset de informações sobre músicas do Spotify.

## Descrição do projeto 
Desenvolvimento de um sistema de recomendação de músicas utilizando a API do Spotify, Python e Spark (MLlib, PySpark, Pandas Spark). O objetivo é demonstrar como essas tecnologias podem ser integradas para criar um recomendador eficaz.

Tudo isso feito no Databricks com um Cluster do Spark 3.3.0 - 11.3 LTS

A arquitetura do projeto é composta pelos seguintes componentes:

1. **Spotify API**: Fonte de dados que fornece informações sobre músicas.
2. **Spark**: Framework de processamento de dados usado para manipulação e análise de grandes volumes de dados.
3. **Python Scripts**: Realizam a extração, transformação e carga (ETL) dos dados.
4. **Modelo de Recomendação**: Algoritmo de machine learning treinado para sugerir músicas.

## Ferramentas Utilizadas

- **Python**: Usado para a lógica ETL e integração com o Spark.
  - **Bibliotecas**:
    - `spotipy`: Para conectar à API do Spotify.
    - `pyspark`: Para processamento e análise de dados com Spark.
    - `pandas`: Para manipulação de dados.
    - `matplotlib`: Para visualizações de dados.
    - `plotly`: Para visualizações interativas de dados.
    - `numpy`: Para operações numéricas.
    - `scipy`: Para cálculos científicos.
    - `skimage`: Para manipulação de imagens.
   
- **Spark**: Framework de processamento de dados para análise e treinamento do modelo de recomendação.
  - **MLlib**: Biblioteca de machine learning do Spark.
    - `Pipeline`: Para criar pipelines de machine learning.
    - `KMeans`: Para clustering.
    - `PCA`: Para análise de componentes principais.
    - `StandardScaler`: Para padronização de dados.
    - `VectorAssembler`: Para transformar colunas de dados em um vetor.
    - `vector_to_array`: Para converter vetores em arrays.
   
  - **PySpark**: Interface do Spark com Python.
- **Spotify API**: Fornece acesso a dados detalhados sobre músicas, álbuns e artistas.
- **Databricks**: Plataforma de análise de dados para execução dos notebooks e integração com Spark.

### Razões para Escolher Estas Ferramentas

- **Python**: Flexível e amplamente utilizado para manipulação de dados e machine learning.
- **Spark**: Ideal para processamento de grandes volumes de dados, permitindo escalabilidade e eficiência.
- **Spotify API**: Fonte rica e confiável de dados musicais, essencial para a criação de um sistema de recomendação de alta qualidade.
- **Databricks**: Plataforma robusta para processamento de dados em larga escala, facilitando a colaboração e a integração com Spark.
