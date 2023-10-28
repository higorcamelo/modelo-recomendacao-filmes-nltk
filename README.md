# Sistema de Recomendação de Filmes com Similaridade de Conteúdo

Este repositório contém um sistema de recomendação de filmes com base em similaridade de conteúdo. O sistema é desenvolvido em Python e utiliza várias bibliotecas e técnicas para realizar recomendações personalizadas de filmes com base no conteúdo de filmes previamente assistidos.

## Processo

O sistema segue o seguinte processo:

1. **Pré-processamento de Dados**: Os conjuntos de dados de filmes e créditos são carregados e fundidos para criar um conjunto de dados combinado.

2. **Engenharia de Recursos**: As informações relevantes, como gêneros, elenco e diretores, são extraídas e normalizadas. Isso garante que os dados estejam prontos para análise.

3. **Análise de Linguagem Natural**: As descrições dos filmes são processadas e transformadas em vetores de recursos usando técnicas de processamento de linguagem natural.

4. **Recomendação de Filmes**: Com base na similaridade entre filmes, o sistema gera recomendações personalizadas para os usuários.

5. **Exibição de Recomendações**: As recomendações são exibidas para os usuários, permitindo que eles descubram filmes com base em suas preferências.

## Tecnologias Utilizadas

O sistema faz uso das seguintes tecnologias e bibliotecas:

- Python: A linguagem de programação principal.
- Pandas: Para manipulação de dados e fusão de DataFrames.
- NumPy: Para cálculos numéricos.
- Scikit-learn: Para análise de linguagem natural e cálculo de similaridade.
- NLTK: Para processamento de linguagem natural.

## DataFrames

O sistema utiliza dois DataFrames principais:

1. **movies.csv**: Este DataFrame contém informações sobre os filmes, incluindo títulos, gêneros e descrições.

2. **credits.csv**: Este DataFrame fornece informações sobre o elenco e a equipe de produção de cada filme.

## Como Usar

Você pode clonar este repositório e executar o código em um ambiente Python. O sistema é capaz de fornecer recomendações de filmes com base nos seus interesses.

**Nota**: Certifique-se de instalar as bibliotecas listadas no arquivo `requirements.txt` antes de executar o código.

