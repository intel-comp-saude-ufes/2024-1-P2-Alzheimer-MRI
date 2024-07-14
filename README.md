# 2024-1-P2-Alzheimer-MRI


<p align="center">
  <img src="dementia-brain-changes-thumb.png" />
</p>


## Resumo
Esse repositório contém o estudo dos dados de demência em um dataset opensource com a informação de 1000 pessoas e 24 features. O trabalho é constituido do tratamento, processamento e exploração dos dados, incluindo modelos de ML e seus resultados.


## Sumário

- [Resumo](#resumo)
- [Sumário](#sumário)
- [Base de dados](#base-de-dados)
- [Instalação](#instalação)
- [Como usar](#como-usar)
- [Resultados](#resultados)
- [Licença](#licença)

## Base de dados

base de dados disponibilizada na plataforma Kaggle sobre as diretrizes da licença "Open Data Commons Open Database License (ODbL) v1.0". Os dados foram levantados manualmente juntando imagens de múltiplas bases de dado. Os dados englobam 6400 imagens de ressonância magnética do cérebro de pessoas divididas nas classes "Mild Demented", "Moderate Demented", "Non Demented" e "Very Mild Demented".

## Instalação

### Ambiente virtual

O pacote `conda` é necessário para criar ambientes virtuais Python. Para instalá-lo siga as instruções disponibilizadas na [Documentação](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

### Obtendo o projeto

Agora, vamos clonar um repositório Git e criar um ambiente virtual Python:

```bash
# Baixe o projeto
git clone https://github.com/intel-comp-saude-ufes/2024-1-P1-dementia.git

# Entre na pasta do projeto
cd 2024-1-P1-dementia/

# Crie um ambiente virtual com nome 'dementia'
conda create -n dementia

# Ative o ambiente virtual
conda activate dementia
```

### Instalando as dependências

Uma vez no ambiente virtual, instale as dependências do projeto:

```bash
conda install pip jupyterlab
pip install -r requirements.txt
```

## Como usar

Para abrir os Jupyter Notebooks que contém o projeto, basta utilizar o projeto [JupyterLab computational environment](https://github.com/jupyterlab/jupyterlab) (já consta como dependência desse trabalho). Para executá-lo, basta digitar no terminal: 

```bash
jupyter-lab
```

Então, abra o browser em: [http://localhost:8888/](http://localhost:8888/). O arquivo [notebooks/project](./notebooks/project.ipynb) que contém todo o código desenvoldido do projeto.

## Resultados 



## Licença

Este projeto é licenciado sob os termos da [licença MIT](./LICENSE) e está disponível gratuitamente.
