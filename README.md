# Spam-Filter

This is an implementation of a spam filter using Naive Bayes classifier with additive smoothing.

The dataset used is a subset of 2005 TREC Public Spam Corpus.

The training set and test set both use the same format: each line represents the space-delimited properties of an email, with
the first one being the email ID, the second one being whether it is a spam or ham (non-spam), and the rest are words and their occurrence numbers in this email. In preprocessing, non-word characters have been removed, and some features have been selected.
