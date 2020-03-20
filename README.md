# Classiﬁcazione di immagini di 102 specie di ﬁori tramite Deep Learning e Auto Machine Learning

[Cristian Baldi](https://www.linkedin.com/in/crisbal/) - [Fabrizio Olivadese](https://www.linkedin.com/in/fabrizio-olivadese-71a445b3/) - Simone Vitali

University Of Milano Bicocca - Department of Computer Sciences, Systems and Communications

## Sommario
L’obiettivo dell’elaborato é la classiﬁcazione di immagini rappresentanti 102 diverse specie di ﬁori. Per raggiungere l’obiettivo sono stati confrontati diversi approcci basati sul **deep learning**, in particolare una rete basata **convluzionale**, una basata su **autoencoder**, una su **ﬁne tuning** e una su **feature extraction**. 

Per decidere la struttura ottimale delle singole reti, cosí come gli iperparametri, sono state utilizzate tecniche di **AutoML e Bayesian Optimization**. La rete che utilizza feature extraction a partire da una VGG16 si dimostra il modello piú eﬃcace, ottenendo performance sul test set pari al **72.7% di accuracy** e 90.3% di top-5 accuracy.

## Introduzione
A diﬀerenza di altri task di classiﬁcazione sulle immagini, che si limitano a distinguere categorie diverse di oggetti, un task come quella dello classiﬁcazione delle specie di ﬁori si preﬁssa di distinguere classi speciﬁche all’interno di una singola categoria di oggetti. Nel caso in questione le classi da identiﬁcare sono caratterizzate da un’elevata similaritá  extra-classe, ad esempio due ﬁori che hanno petali e colore simile potrebbero appartenere a specie diverse.

Per raggiungere l’obbiettivo preﬁssato, diversi modelli vengono proposti, addestrati ed ottimizzati con tecniche di Automated Machine Learning al ﬁne di **individuare gli iperparametri e la struttura delle reti ottimali.** I modelli vengono poi confrontati per individuare il migliore, sia in termine di accuracy che di top-5-accuracy. In particolare vengono confrontati un modello ideato da zero, un modello basato su un autoencoder convoluzionale, un modello che usa la rete VGG16 come feature extractor ed un modello basato sul ﬁne tuning sempre della rete VGG16.

## Report Completo

[Leggi il report completo qui](https://github.com/Fabrolly/Machine-Learning-Model-to-Predicting-Used-Cars-Prices/blob/master/Final%20Report.pdf)
