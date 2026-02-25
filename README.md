# Projeto Ciência de Dados

Este projeto realiza uma análise exploratória de dados (EDA) de um banco cinematográfico e constrói um modelo preditivo para estimar a nota do IMDB dos filmes. O objetivo é fornecer orientações sobre que tipo de filme deve ser produzido.

### Instalação

Passo 1: Clone este repositório:
```
git clone https://github.com/CamillySR/LH_CD_CamillySilva.git
cd LH_CD_CamillySilva
```
Passo 2: Instale os pacotes necessários:

```
pip install -r requirements.txt

```
### Como Executar

1. Abra o Jupyter Notebook:
```
jupyter notebook
```

2. Abra os notebooks:
- eda_modelagem.ipynb
- teste_modelo.ipynb

3. Para usar o modelo no Jupyter ou semelhantes:
```
import pickle

with open("modelo.pkl", "rb") as arquivo:
    modelo = pickle.load(arquivo)
```
