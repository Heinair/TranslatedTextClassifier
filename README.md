# TranslatedTextClassifier

EN 🇬🇧 - Machine learning based approach to determine whether or not a book or a chunk of text was written in French or has been translated from English.

We tried several approaches, but the best approach I could find was to vectorize the text with sci-kit learn CountVectorizer and then train a Naive Bayes classifier 
with these vectors. The results seem pretty good with accuracies between 97-99.5% using ~800-1000MB of text data to train it and 50-200MB to test it.

More details about the problematic in the SUBJECT.pdf and about our solutions in the RAPPORT.pdf (both are written in French) 


all data used (txtO->original, txtT-> translated) : https://www.dropbox.com/sh/o6rk17da6x07yj1/AABenQE-lrIZUsmFkXT-Vju3a?dl=0 

FR 🇫🇷 - Approche en apprentissage automatique afin de déterminer si un texte est nativement écrit en français ou s'il a été traduit depuis l'anglais.

Nous avons essayés de multiples approches, mais la meilleure à laquelle je sois parvenue est de vectoriser le text avec la méthode CountVectorizer issue de sci-kit learn puis d'entrainer un modèle de classification bayésien avec ces derniers. Les résultats sont plutôt bons, avec des précisions variant de 97-99.5% en utilisant ~800-1000MB de données textuelles pour l'appretissage et 50-200MB pour la phase de test

Plus de détails sur la problématique dans le fichier SUBJECT.pdf and about our solutions in RAPPORT.pdf

Toutes les données utilisées (txtO->original, txtT-> traduit) : https://www.dropbox.com/sh/o6rk17da6x07yj1/AABenQE-lrIZUsmFkXT-Vju3a?dl=0 
