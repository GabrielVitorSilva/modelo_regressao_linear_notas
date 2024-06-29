# Modelo de Regressão Linear para Previsão de Notas

Este repositório contém um projeto de machine learning que implementa um modelo de regressão linear para prever notas de alunos. O objetivo do projeto é analisar dados educacionais e construir um modelo preditivo que possa ajudar a identificar fatores que influenciam o desempenho acadêmico.

## Descrição do Projeto

O projeto utiliza um conjunto de dados de notas de alunos e várias características (features) que podem afetar o desempenho acadêmico. Através da análise exploratória de dados e da construção de um modelo de regressão linear, buscamos prever as notas dos alunos com base nessas características.

## Estrutura do Repositório

- `datasets/`: Contém os conjuntos de dados utilizados no projeto.
- `README.md`: Este arquivo, contendo a descrição do projeto e instruções de uso.

## Instalação

Para rodar o projeto localmente, siga os seguintes passos:

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/modelo_regressao_linear_notas.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd modelo_regressao_linear_notas
    ```
3. Crie e ative um ambiente virtual (recomendado):
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use: venv\Scripts\activate
    ```
4. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

Os notebooks no arquivo modelo_pontuacao.ipynb contêm o fluxo de trabalho completo, incluindo a análise exploratória de dados, a construção e avaliação do modelo de regressão linear. Para visualizar e executar os notebooks, use o Jupyter Notebook:

```bash
jupyter notebook modelo_pontuacao.ipynb
