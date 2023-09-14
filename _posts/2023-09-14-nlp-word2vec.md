---
title: "Word2vec"
date: 2023-09-14
---

- Link to original paper: [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf)
- Things I learned:
  - word2vec doesn't use non-linear layer.
  - log-bilinear language model is a language model that predicts a word by summing up word representations of previous words (let's call it a context vector) and finding a word that has the most similar representation as this context vector. (refer to 9p. of slide[http://www.cs.utoronto.ca/~hinton/csc2535/notes/hlbl.pdf])
  
