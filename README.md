# de-nlp-train-set
This is a toolset to create a German NLP training set with labels from the German wikipedia. The resulting dataset can be downloaded below. It contains 533,842 training samples and 60,000 test samples.

The goal is to supply a big german dataset as a reference for NLP experiments. This way different deep learning networks and techniques like preprocessing can be compared. The program files are jupyter notebooks (including the output) so you can see what happened during execution.

This is a binary classification task with the following two labels:
- gesch for "Geschichte" - the german word for history
- gesell for "Gesellschaft" - the german word for society

The texts belong to exactly one of these categories and have to be classified.

## Workflow how this Dataset has been created
The workflow on how this dataset has been created is described in the wiki here: https://eniak.de/it/creating_a_big_german_dataset_as_a_reference_for_nlp_experiments

## Download Dataset
The dataset can be downloaded here: https://eniak.de/download/nlp-train-set/text-data.zip

It contains the following 4 directories:
- gesch_train - with 266,921 training samples for category "gesch"
- gesell_train - with 266,921 training samples for category "gesell"
- gesch_test - with 30,000 test samples for category "gesch"
- gesell_test - with 30,000 test samples for category "gesell"

The filename is the id of the wikipedia article. It can be viewed when you enter https://de.wikipedia.org/wiki?curid=10 and replace the suffix number of the URL with the file name number.
