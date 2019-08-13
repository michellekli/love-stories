# Report
[![Report.](https://github.com/michellekli/love-stories/blob/master/report-preview.png)](https://github.com/michellekli/love-stories/blob/master/Modeling%20versus%20Clustering%20for%20Text%20Classification.pdf)

# Introduction
This repo houses a two-notebook project on novels obtained from Project Gutenberg. In this project, I compare modeling and clustering for text classification and conclude that modeling is superior to clustering for this task. [Part 1](https://github.com/michellekli/love-stories/blob/master/love-stories-part1.ipynb) covers data cleaning. [Part 2](https://github.com/michellekli/love-stories/blob/master/love-stories-part2.ipynb) covers feature creation, model evaluation, and clustering evaluation.

# Results
## Multinomial Naive Bayes achieves 90.8% accuracy, which is ~40% higher than spectral clustering.
![Multinomial Naive Bayes has the highest accuracy score of 90.8%.](https://github.com/michellekli/love-stories/blob/master/plots/love-stories-part2-model-holdout.png)

## Spectral clustering correctly classifies some authors more than others.
![Spectral clustering correctly classifies some authors more than others.](https://github.com/michellekli/love-stories/blob/master/plots/love-stories-part2-author-stabilities.png)

## Observations with higher prediction stability are more likely to be correctly classified.
![Observations with higher prediction stability are more likely to be correctly classified.](https://github.com/michellekli/love-stories/blob/master/plots/love-stories-part2-prediction-stabilities.png)

# Data Set
The data set consists of 10 novels downloaded from Project Gutenberg. They were all found within the first few pages of the ["Books about Love stories (sorted by popularity)"](https://www.gutenberg.org/ebooks/subject/2487) list.
* Pride and Prejudice, by Jane Austen
* Villette, by Charlotte Brontë
* The Woman in White, by Wilkie Collins
* Middlemarch, by George Eliot
* Wives and Daughters, by Elizabeth Cleghorn Gaskell
* Jude the Obscure, by Thomas Hardy
* The Portrait of a Lady, by Henry James
* The Lost Girl, by D. H. Lawrence
* The Age of Innocence, by Edith Wharton
* The Voyage Out, by Virginia Woolf
