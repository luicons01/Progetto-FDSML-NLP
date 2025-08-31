# Progetto-FDSML-NLP
Progetto combinato per i corsi di fondamenti di data science e machine learning, e natural language processing. Il progetto tratta l'anonimizzazione dei dati sensibli.

## Overview
Questo progetto combinato è stato sviluppato per gli esami di Fondamenti di Data Science e Machine Learning (FDSML) e di Natural Language Processing (NLP). L'obiettivo principale di questo progetto è l'utilizzo di specifiche tecniche per l'addestramento di modelli di Machine Learning e per l'anonimizzazione di dati sensibili. 

## Autori
<a href="https://github.com/luicons01/Progetto-FDSML-NLP/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=luicons01/Progetto-FDSML-NLP" />
</a>

* [Consiglio Luigi](https://github.com/luicons01)
* [Francesco Ferrara](https://github.com/Rokuoganz)

## Obiettivi
- Comprendere come si comportano i principali modelli di ML di fronte a dati sanitari.
- Comprendere se è possibile anonimizzare correttamente i dati personali dei pazienti.

## Dataset
Il dataset usato in questo studio cataloga vari URL in: URL di phishing e URL legittimi. Questa catalogazione è fatta attraverso la variabile label che, quando vale 0 indica un sito di phishing e 1 nel caso di sito legittimo. Il dataset presenta altre variabili che potrebbero permettere un'identificazione prematura di questi URL come la lunghezza degli stessi, il numero di riferimenti esterni/interni, il numero di caratteri speciali ecc.

## Strumenti e Tecnologie
- Python: il linguaggio tramite il quale è stato scritto il codice.
- Google Colab: ambiente di sviluppo.
- IPYNB: ossia python notebook, permette di strutturare il codice in maniera agevola.

## Installazione e Uso
1. Scaricare i file .ipynb e il dataset .csv e il file .json.
2. Aprire i file .ipynb tramite Google Colab.
3. Caricare i dataset su Colab: per il file 'ProgettoHealthcareDataset.ipynb' va caricato solo il file healthcare_dataset.csv, mentre per il file 'ProgettoHealthcareDatasetNLP.ipynb' va caricato anche 'goldDataPerson.json'
4. Eseguire tutte le celle tramite Colab

## Struttura del Progetto
- `ProgettoHealthcareDataset.pdf`: Documentazione del progetto combinato completo.
- `ProgettoHealthcareDatasetNLP.pdf`: Documentazione del progetto di NLP.
- `Codici/`: Directory contenente i file .pynb.
- `Dataset/`: Directory contenente il dataset e il file .json.
