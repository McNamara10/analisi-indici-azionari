# Analisi degli indici azionari: S&P 500 ed EURO STOXX 50

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/McNamara10/analisi-indici-azionari/blob/main/analisi_indici_azionari.ipynb)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![pandas](https://img.shields.io/badge/pandas-data%20analysis-lightgrey)
![yfinance](https://img.shields.io/badge/yfinance-market%20data-green)
![matplotlib](https://img.shields.io/badge/matplotlib-visualization-orange)
![seaborn](https://img.shields.io/badge/seaborn-visualization-teal)

## Descrizione

Analisi esplorativa della performance storica di due indici azionari globali:
- **S&P 500** (`^GSPC`): le 500 maggiori aziende quotate negli USA
- **EURO STOXX 50** (`^STOXX50E`): le 50 maggiori aziende dell'Eurozona

I dati vengono scaricati direttamente da Yahoo Finance tramite `yfinance` e coprono il periodo dal 2000 ad oggi per l'S&P 500 e dal 2007 per l'EURO STOXX 50.

## Struttura dell'analisi

| # | Sezione |
|---|---------|
| 1 | Setup e acquisizione dati |
| 2 | Preprocessing: pulizia date e colonne ausiliarie |
| 3 | Rendimenti annuali e mensili |
| 4 | Rendimenti giornalieri e stagionalità settimanale |
| 5 | Refactoring: funzioni riutilizzabili |
| 6 | Visualizzazioni (bar chart, heatmap, istogramma) |
| 7 | Analisi comparativa |
| 8 | Conclusioni |

## Installazione

```bash
pip install -r requirements.txt
```

## Esecuzione

Il notebook è eseguibile in locale con VSCode + estensione Jupyter, oppure direttamente su Google Colab cliccando il badge in cima.
