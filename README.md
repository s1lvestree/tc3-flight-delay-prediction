# Flight Delay Prediction

Notebook para prever atrasos em voos.

## Dataset
Link para baixar dataset flights.csv: https://drive.google.com/drive/folders/1aS7exW5N0qq1uIxvIBcAfc18OHojOMjj?usp=sharing

Crie a pasta "data" dentro da raiz do projeto, e aloque todos os .csv disponíveis para download.

Dataset de voos contendo informações como:

- companhia aérea
- aeroporto de origem
- aeroporto de destino
- horário de partida
- distância do voo
- atraso na chegada

## Preparar ambiente
Crie e ative um ambiente virtual:

### Linux / macOS
``` bash
python3 -m venv venv
source venv/bin/activate
```
### Windows
``` bash
python -m venv venv
venv\Scripts\activate
```
### Instale as dependências:
``` bash
pip install -r requirements.txt
```
## Execução do notebook

Inicie o Jupyter Notebook:
``` bash
jupyter notebook
```
Depois abra o arquivo:

-  tc3.ipynb
  
Execute as células em ordem, ou use a opção:

- Kernel > Restart & Run All

## Modelos utilizados

- Logistic Regression
- Random Forest

## Métricas avaliadas

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Tecnologias

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
