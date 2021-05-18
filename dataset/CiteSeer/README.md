# Citeseer Dataset

This directory contains a selection of the CiteSeer dataset, which consists in a collection of scientifical papers, together with the citations between them.

These papers are classified into one of the following six classes:

- Agents
- AI
- DB
- IR
- ML
- HCI

The papers were selected in a way such that in the final corpus every paper cites or is cited by atleast one other paper. There are 3312 papers in the whole corpus and there are 4732 edges.
After stemming and removing stopwords we were left with a vocabulary of size 3703 unique words. All words with document frequency less than 10 were removed.

## Content

This directory contains a split of the whole dataset, which we subdivided into three distinct parts:

- Training: the subset of the Dataset that we used to train our models;
- Validation: the subset of the Dataset that we use to estimate the test error during training. We use this estimate to understand when it's time to stop training.
- Test: the subset of the Dataset that we evaluate our model on.
