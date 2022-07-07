# DMWPublicPres_Ambag
DMW Public Presentation with Term 2 LT4 (Joaquin Gonzales, K-Ann Carandang, John Gacal, Manu Gaspar and Weddy Diamada).


Executive Summary

In this report, we scraped data from the House of Representatives website to extract all bills and its features from 01 July 2019 to 30 August 2021. We pre-processed the data to tokenize, lemmatize, remove stop words using RegexpTokenizer and Spacy libraries, and then constructed a TF-IDF matrix. We then performed dimensionality reduction using Latent Semantic Analysis to truncate the data that would be used for clustering analysis using 90% cumulative variance as threshold. Agglomerative clustering was used to determine and surface the clusters and themes from more than the 9000 documents that we scraped.
