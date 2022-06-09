# TranslatedTextClassifier
Machine learning based approach to determine whether or not a book or a chunk of text was written in French or has been translated from English.
We tried several approaches, but the best approach I could find was to vectorize the text with sci-kit learn CountVectorizer and then train a Naive Bayes classifier 
with these vectors. The resulst seems pretty good with accuracies between 97-99.5% using ~800-1000MB of text data to train it and 50-200MB to test it.

More details about the problematic in the SUBJECT.pdf and in our solutions in the RAPPORT.pdf (both are written in French) 


https://www.dropbox.com/sh/o6rk17da6x07yj1/AABenQE-lrIZUsmFkXT-Vju3a?dl=0 : all data used (txtO->original, txtT-> translated)