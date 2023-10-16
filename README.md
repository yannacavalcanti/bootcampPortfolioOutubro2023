# BootCamp:  Crie seu Portfólio em Ciência de Dados

**Autora**: Yanna Cavalcanti

**Launch**: Outubro de 2023

Seja bem-vindo(a) ao nosso BootCamp de Ciência de Dados. O BootCamp surgiu de uma necessidade iminente de trazer um treinamento **intensivo** de **aplicações práticas** para todos os que desejam se especializar nesta área tão rica e abrangente que é a ciência de dados.
O grande desafio de quem está ingressando na área de dados é a grande quantidade de conteúdo disponível e a dificuldade de encontrar um caminho que seja **prático** e **direto** para a aplicação dos conceitos aprendidos. Por isso, o BootCamp de Ciência de Dados foi criado para ser um guia prático de aprendizado, com projetos que vão te ajudar a **construir ou ampliar** seu portfólio de de ciência de dados.

O BootCamp é composto por 4 módulos, cada um com um case de aplicação e abordagens variadas. São eles:

- **Case 1**: Projeto de regressão
- **Case 2**: Projeto de clusterização
- **Case 3**: Projeto de classificação
- **Case 4**: Projeto de séries temporais

A resolução de cada case ocorrerá da seguinte forma:
- **Passo 1**: Envio do problema em formato de notebook (+ aulas de contexto na plataforma) a ser resolvido pelo aluno
- **Passo 2**: Suporte para dúvidas e resolução de problemas através do canal do Discord referente ao Case (#duvidas-case-[ref_do_case])
- **Passo 3**: Envio do notebook com a solução completa (aqui sugerimos que o aluno utilize a solução apenas para ajudá-lo a compreender o que não conseguiu fazer sozinho) (+ aulas de resolução na plataforma)
- **Passo 4**: Comparação da sua solução com a proposta e suporte para dúvidas remanescentes pelo Discord

Os cases foram criados a partir de datasets públicos, disponíveis no Kaggle. Em cada notebook, você encontrará o link para download.

## Setup

A primeira semana do BootCamp será dedicada a Setup. Nesta semana, você vai aprender a configurar seu ambiente de trabalho para rodar os notebooks e a instalar as bibliotecas necessárias para a resolução dos cases.

A sugestão para quem está no nível iniciante é que você utilize o **Kaggle** para rodar os notebooks. 

Para quem está no nível intermediário ou avançado, sugerimos que você utilize o seu **PC local junto ao Anaconda ou Miniconda**, de acordo com o sistema operacional do seu computador.

Para qualquer dúvida relacionada ao setup, você pode entrar no canal do Discord #duvidas-setup e pedir ajuda.

### Opção 1 [Nível básico]: Kaggle
Para rodar os notebooks no Kaggle, você vai precisar:
- Criar uma conta 

  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/)
- Entrar no link do Kaggle referente a cada dataset/problema
- Fazer o download do notebook do GitHub e subir no Kaggle

O dataset já estará no Kaggle e você só precisará fazer a ligação com a pasta do dataset no seu notebook.

### Opção 2 [Nível intermediário]  : PC Local
Para rodar os notebooks no seu PC local, você vai precisar:
- Fazer o download do dataset no Kaggle
- Clonar o repositório do GitHub

**Windows**:
- [Instalar o Anaconda](https://www.anaconda.com/products/individual)
- [Criar um ambiente virtual](https://docs.anaconda.com/free/navigator/getting-started/#navigator-managing-environments)
- [Instalar as bibliotecas necessárias do arquivo `requirements.txt`](https://docs.anaconda.com/free/navigator/getting-started/#navigator-managing-packages)

**Linux/MacOS**:
- Criar um conda environment

    ```conda create --name bootcamp python=3.8```
- Ativar o conda environment
    
    ```conda activate bootcamp```
- Instalar as bibliotecas necessárias (requirements.txt)
        
    ```pip install -r requirements.txt```
- Instalar o iPython Kernel para disponibilizar o conda environment no Jupyter Notebook

    ```conda install -c anaconda ipykernel```
- Criar o Kernel do conda environment

    ```python -m ipykernel install --user --name=bootcamp```
- Instalar o Jupyter Notebook

    ```conda install -c conda-forge notebook```
- Abrir o Jupyter Notebook e selecionar o Kernel do conda environment criado

    ```jupyter notebook```


### Opção 3: Google Colab
Para rodar os notebooks no [Google Colab](https://colab.research.google.com/?utm_source=scs-index), você vai precisar:
- Fazer o download do dataset no Kaggle
- Fazer o upload do dataset no Google Colab
- Fazer o download do notebook do GitHub e subir no Google Colab
- Fazer o upload do notebook no Google Colab
- Fazer a ligação com a pasta do dataset no seu notebook
- Garantir que todas as bibliotecas necessárias estão instaladas no Google Colab