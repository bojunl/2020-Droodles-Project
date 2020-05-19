# 2020-Droodles-Project
Generate jokes from images


Resources used

Google Quick Draw Dataset
https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap

Language Corpus (Conan O'Brien's jokes)
https://github.com/brendansudol

Google News Word Embeddings
http://vectors.nlpl.eu/repository/

Stanford POS Tagger
https://nlp.stanford.edu/software/tagger.shtml



Droodles_DataPreprocessing+ClassificationModel performs data-preprocessing on the Google Quick Draw dataset and builds image classification model. 
Droodles_ObjectIdentification identifies 2 objects from the image and saves the result to identified.txt.
Droodles_LanguageGenerationModel builds an LSTM based natural language generating model with Conan O'Brien's jokes as language corpus.
Droodles_RepetitiveTextGeneration generates jokes and replaces the nouns in the sentences with identified objects.
