# Projeto de Ciência de Dados e Big Data

Este projeto foca na aplicação de técnicas de Ciência de Dados e Big Data utilizando **Python**, **JupyterLab**, **Pandas**, e **SQLite**. O objetivo é permitir a análise e manipulação de grandes volumes de dados, explorar insights e criar visualizações ricas para facilitar a tomada de decisões.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação poderosa e flexível, amplamente utilizada em projetos de Ciência de Dados.
- **JupyterLab**: Ambiente interativo para trabalhar com notebooks, onde é possível combinar código, visualizações e explicações em um único documento.
- **Pandas**: Biblioteca fundamental para manipulação e análise de dados estruturados.
- **NumPy**: Biblioteca para computação numérica, essencial para trabalhar com arrays e realizar operações matemáticas eficientes.
- **Matplotlib**: Biblioteca para criação de gráficos e visualizações estáticas.
- **Seaborn**: Biblioteca de visualização baseada no Matplotlib, voltada para gráficos estatísticos e mais interativos.
- **Scikit-learn**: Biblioteca poderosa para algoritmos de aprendizado de máquina, análise preditiva e estatística.
- **SQLite**: Banco de dados relacional embutido, ideal para trabalhar com grandes volumes de dados sem a necessidade de um servidor de banco de dados separado.

## Objetivo do Projeto

O objetivo deste projeto é demonstrar como usar as ferramentas acima para:

1. Analisar grandes volumes de dados (Big Data) de maneira eficiente.
2. Explorar e manipular dados usando **Pandas**.
3. Realizar análises estatísticas e preditivas com **Scikit-learn**.
4. Criar visualizações interativas e informativas com **Matplotlib** e **Seaborn**.
5. Armazenar e consultar dados usando **SQLite** para ambientes de dados menores a médios.

## Requisitos

Antes de começar, é necessário que você tenha o **Python** instalado na sua máquina. Você pode verificar se o Python está instalado e qual versão está utilizando com o comando:

```bash
python --version
````

Para instalar o Python, siga as instruções no [site oficial](https://www.python.org/downloads/).

## Instalação das Dependências

Para garantir que todas as dependências do projeto sejam instaladas corretamente, siga os passos abaixo:

1. **Instalar o JupyterLab**

   O JupyterLab é um ambiente interativo onde você pode criar e executar notebooks. Para instalá-lo, execute o seguinte comando no terminal:

   ```bash
   pip install jupyterlab
   ```

2. **Instalar Bibliotecas Essenciais para Ciência de Dados**

   Em seguida, instale as bibliotecas necessárias para manipulação de dados, visualizações e aprendizado de máquina. Execute o seguinte comando:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

   Aqui está o que cada biblioteca faz:

   * **Pandas**: Fornece estruturas de dados eficientes e fáceis de usar, como DataFrames, que são essenciais para análise de dados.
   * **NumPy**: Oferece suporte a matrizes multidimensionais e funções matemáticas de alto desempenho.
   * **Matplotlib**: Usada para gerar gráficos e visualizações, sendo muito útil na criação de gráficos como linhas, barras e histogramas.
   * **Seaborn**: Expande o Matplotlib para criar gráficos estatísticos mais sofisticados com mais facilidade.
   * **Scikit-learn**: Biblioteca que fornece ferramentas para aprendizado de máquina, como algoritmos de classificação, regressão, agrupamento, entre outros.

3. **Instalar SQLite** (caso necessário)

   SQLite é um banco de dados leve, ideal para ambientes de dados menores a médios. Para instalar o pacote SQLite, use:

   ```bash
   pip install sqlite
   ```

## Acessando o JupyterLab

Depois de instalar todas as dependências, você pode iniciar o JupyterLab com o seguinte comando:

```bash
jupyter lab
```

Isso abrirá o JupyterLab em seu navegador padrão, onde você poderá criar e editar notebooks interativos. O JupyterLab permite a execução de código em Python, visualização de gráficos e execução de consultas SQL, entre outras funcionalidades, tudo em um único ambiente.

## Estrutura do Projeto

A estrutura do seu projeto pode ser organizada da seguinte forma:

```
/project-directory
    /DataBase                # Arquivos de banco de dados SQLite
    /notebooks               # Notebooks Jupyter
    .gitignore               # Arquivo para ignorar arquivos indesejados
    README.md                # Este arquivo
    main.py                  # Arquivo principal para execução do código
    requirements.txt         # Arquivo com as dependências do projeto
```

* **DataBase/**: Contém os arquivos do banco de dados SQLite.
* **notebooks/**: Pasta para armazenar os notebooks Jupyter com análise e visualização de dados.
* **main.py**: Arquivo Python principal que pode ser usado para rodar scripts que não exigem notebooks.
* **requirements.txt**: Arquivo que contém todas as dependências necessárias, caso você precise configurar um ambiente virtual.