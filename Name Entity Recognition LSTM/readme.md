### Problem Statement
In Natural Language Processing (NLP), Entity Recognition is one of
the common problems. NER is a method of extracting the relevant
information from a large corpus and classifying those entities into
predefined categories such as location, organization, name, and so
on.
In this problem you are given tagged data for entities, you have to
predict those entities using LSTM models.

### Dataset Description
Dataset: CRF_POS_dataset.csv
This dataset is extracted from GMB(Groningen Meaning Bank) corpus, which is tagged,
annotated, and built specifically to train the classifier to predict named entities such as name,
location, etc. All the entities are labelled using the BIO scheme, where each entity label is
prefixed with either B or I letter. B- denotes the beginning and I- inside of an entity. The words
which are not of interest are labelled with 0 – tag.
The below table shows detailed information about the labels of the words.
