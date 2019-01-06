# de-nlp-train-set
This is a toolset to create a German NLP training set with labels from the German wikipedia. The resulting dataset can be downloaded below. The goal is to supply a big german dataset as a reference for NLP experiments. This way different deep learning networks and techniques like preprocessing can be compared. The program files are jupyter notebooks (including the output) so you can see what happened during execution.

This is a binary classification task with the following two labels:
- gesch for "Geschichte" - the german word for history
- gesell for "Gesellschaft" - the german word for society

The texts belong to exactly one of these categories and have to be classified.

## Workflow how this Dataset has been generated

## Download Dataset
The dataset can be downloaded here: https://eniak.de/download/nlp-train-set/text-data.zip

It contains the following 4 directories:
- gesch_train - with 266,921 samples
- gesell_train - with 266,921 samples
- gesch_test - with 30,000 samples
- gesell_test - with 30,000 samples

The filename is the id of the wikipedia article. It can be viewed when you enter https://de.wikipedia.org/wiki?curid=10 and replace the suffix number of the URL with the file name number.
