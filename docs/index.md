---
layout: default
title: ARTIFICIAL INTELLIGENCE
author: Alfredo Canziani
lang-ref: home
---

**CSCI-UA 0472 · SPRING 2024 · [COURANT INSTITUTE OF MATHEMATICAL SCIENCES](https://cims.nyu.edu/)**

| INSTRUCTOR  | Alfredo Canziani, Ernest Davis                                   |
| LECTURES    | Monday & Wednesday 11:00 – 12:15, Zoom                           |
| MATERIAL    | [2024 repo](https://github.com/Atcold/NYU-AISP24)                |


## Context

It's January 2024. I come back from the Winter Break and… I'm promoted to full-teaching faculty with new duties, including teaching an undergraduate Artificial Intelligence (AI) course here at NYU. We merged two offerings of this course and split the content among the two instructors. Ernie covered the Knowledge-Based AI part in the first half of the semester, while I took care of the Learning-Based AI & Natural Language Processing (NLP) bit. This second half of the course is what I'm releasing to the public.
Working on this course and teaching my Deep Learning one took *all* my time. Therefore, I made no progress on the Energy-Based Deep Learning book this Spring semester.


## Lectures
<style>
    .reads ul  {
  padding-left: 12pt;
  opacity: 0.5;
}
</style>
**Legend**: 🖥 slides, 📝 notes, 📓 Jupyter notebook, 🎥 YouTube video.

{: .reads}

 1. Course first part recap, Naïve Bayes intro
 2. Discrete probability recap, Naïve Bayes classification
    - RN, chapter 12 – Quantifying uncertainty
 3. Naïve Bayes parameters estimation and Laplace smoothing
 4. Binary classifier evaluation, binary Perceptron
 5. Multiclass perceptron, binary and multiclass logistic regression
 6. Optimisation (gradient ascent)
 7. Statistical natural language processing
    - RN, chapter 23 – Natural language processing\
      Sections 23.1.0–23.1.4, 23.1.7, 23.6
    - JM, chapter 3 – N-gram language model\
      Sections 3.0–3.6
 8. Digit captioning
    - Read programming assignment 4
 9. Classification with neural nets
    - YouTube animations made by my high-schooler: vid1, vid2.
    - PyTorch tensor tutorial notebook.
    - PyTorch classification notebook.
 10. Language sampling and neural NLP
     - JM, chapter 3 – N-gram language model\
       Section 3.4
     - JM, chapter 6 – Vector semantics and embeddings\
       Sections 6.0, 6.3, 6.4, 6.9–6.11
     - RN, chapter 23 – Natural language processing\
       Section 23.1.5
     - RN, chapter 24 – Deep learning for NLP\
       Sections 24.0, 24.1, 24.2.0
 11. Convolutional nets + NB
     - PyTorch convnet tutorial notebook.
 12. Recurrent nets + NB
     - PyTorch recurrent net tutorial notebook.
 13. Recurrent nets for NLP and attention
     - RN, chapter 24 – Deep learning for NLP\
       Sections 24.2–24.6


## Suggested readings
<style>
    ul  {
  padding-left: 12pt;
}
</style>
 - RN: **Russell & Norvig** – [Artificial Intelligence, 4th edition](https://aima.cs.berkeley.edu/)
 - JM: **Jurafsky & Martin** – [Speech and Language Processing, 3rd draft](https://web.stanford.edu/~jurafsky/slp3/)
 - Books recommended during episode 13 (last class)
    - **François Fleuret** – [The Little Book of Deep Learning](https://fleuret.org/francois/lbdl.html)
    - **Sebastian Raschka**
       - [Machine Learning Q and AI](https://leanpub.com/machine-learning-q-and-ai/)
       - [Machine Learning with PyTorch and Scikit-Learn](https://www.packtpub.com/product/machine-learning-with-pytorch-and-scikit-learn/9781801819312)
       - [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch)