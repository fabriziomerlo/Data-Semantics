# Project of Data Semantics
## Information extraction from fantasy novels
The pipeline consists of a first step of Named Entity Recognition applied to the seven books of the well-known fantasy text "Harry Potter", in order to define the main entities within the novel with the relative evaluation of the results, a second step of Named Entity Linking in order to connect the different entities found in DBpedia, with the related SPARQL queries for performance evaluation.
In the third step the entities recognized through NER will be used for the creation of word embeddings models: in particular, the creation of word2vec models is envisaged in order to be able to analyze the similarities between terms within the same text and the comparison with another belonging text to the same literary genre: the intention is to be able to apply CADE to align the corpus made up of the "Harry Potter" books 
with a second corpus made up of the books of "The Lord of the Rings". The purpose of this third step is to be able to evaluate if the lexical / grammar context of the two texts, on the performance of the models and also carry out an analysis between similarities and present between the two texts.

