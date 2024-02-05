# gemstones-cnn
Dataset, funzioni ausiliarie e implementazione di una CNN per il riconoscimento di gemme

In questo repository sono contenuti 3 dataset:
- dataset-expanded: contiene 4400 immagini di gemme, è caricato anche su [Kaggle](https://www.kaggle.com/datasets/fransell/gemstones-images-expanded)
- dataset-nogb: dataset contentente le 4400 immagini tutte con sfondo bianco
- dataset-cropped: dataset contentente le immagini ritagliate intorno alla pietra

Il repository contiene anche:
- il codice utilizzato per la generazione di dataset-nogb (tempo impiegato di circa 2 ore)
- il codice utilizzato per la generazione di dataset-cropped
- il notebook Jupyter con l'implementazione della rete neurale convolutiva per la classificazione delle 88 classi di gemme
- un'immagine che rappresenta un granato rosso, entranea al dataset, per effettuare una predizione di esempio
