# Classificazione di immagini di 102 specie di fiori

Cristian Baldi - Fabrizio Olivadese - Simone Vitali

Advanced Machine Learning
University Of Milano Bicocca - Department of Computer Sciences, Systems and Communications

## Sommario
L’obiettivo dell’elaborato `e la classiﬁcazione di immagini rappresentanti 102 diverse specie di ﬁori. Per raggiungere l’obiettivo sono stati confrontati diversi approcci basati sul deep learning, in particolare una rete basata convluzionale, una basata su autoencoder, una su ﬁne tuning e una su feature extraction. Per decidera la struttura ottimale delle singole reti, cos`ı come gli iperparametri, sono state utilizzate tecniche di AutoML e Bayesian Optimization. La rete che utilizza feature extraction a partire da una VGG16 si dimostra il modello pi`u e ﬃ cace, ottenendo performance sul test set pari al 72.7% di accuracy e 90.3% di top-5 accuracy.

## Introduzione
L’obiettivo del progetto `e la realizzazione di una rete neurale convoluzionale per la classiﬁcazione di 102 specie di ﬁori. A diﬀerenza di altri task di classiﬁcazione sulle immagini, che si limitano a distinguere categorie diverse di oggetti, un task come quella dello classiﬁcazione delle specie di ﬁori si preﬁssa di distinguere classi speciﬁche all’interno di una singola categoria di oggetti. Nel caso in questione le classi da identiﬁcare sono caratterizzate da un’elevata similarit`a extra-classe, ad esempio due ﬁori che hanno petali e colore simile potrebbero appartenere a specie diverse; possiamo trovare diﬀerenze rilevanti anche in intra-classe, ad esempio due ﬁori della stessa specie, a seconda dell’ambiente in cui sono cresciuti o delle condizioni atmosferiche di quando la foto ´e stata scattata, potrebbero avere manifestazion diverse.

Per raggiungere l’obbiettivo preﬁssato, diversi modelli vengono proposti, addestrati ed ottimizzati con tecniche di Automated Machine Learning al ﬁne di individuare gli iperparametri e la struttura delle reti ottimali. I modelli vengono poi confrontati per individuare il migliore, sia in termine di accuracy che di top-5-accuracy. In particolare vengono confrontati un modello ideato da zero, un modello basato su un autoencoder convoluzionale, un modello che usa la rete VGG16 come feature extractor ed un modello basato sul ﬁne tuning sempre della rete VGG16.

Il report comleto é disponibile nel pdf qui presente
