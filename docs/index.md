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

 1. Course first part recap, Naïve Bayes intro [🖥](https://drive.google.com/file/d/1e95u-ZCkYYjQJFyAVt2GOkJYhM5eHxFS/) [🖥](https://drive.google.com/file/d/1KPNJgXeYQq2whucIFwuKIY1SJi0m3tJ5/) [🎥](https://youtu.be/jgmaQiVBBEE)
 2. Discrete probability recap, Naïve Bayes classification [🖥](https://drive.google.com/file/d/1JeicRQ0-QL_IZvZOb_U0SktvVKi99VlS/) [🖥](https://drive.google.com/file/d/18mGpD4g6qZeVnmquPFRB4c8vaK2eWQCv/) [📝](https://drive.google.com/file/d/1vNzW9j8jLRYBkCjMkhKKjAUcBKH5jVad/) [🎥](https://youtu.be/ys-G9uEW3O0)
    - RN, chapter 12 – Quantifying uncertainty
 3. Naïve Bayes parameters estimation and Laplace smoothing [🖥](https://drive.google.com/file/d/1W_yOXxluoy95JdLlPLyC4pEPZBdyDpaN/) [🎥](https://youtu.be/xkS9GyujiqQ)
 4. Binary classifier evaluation, binary Perceptron [🖥](https://drive.google.com/file/d/1Btb5d3sKxLmjJkpllRRP-OLAX01LodMb/) [🖥](https://drive.google.com/file/d/1B98r5-cY-sZPPZcoWibbOmwl9Nfe0vYy/)
 5. Multiclass perceptron, binary and multiclass logistic regression [🖥](https://drive.google.com/file/d/1SKWC1ZtHXq6_PzjWVZGzYRVzqau8KKjS/) [🖥](https://drive.google.com/file/d/1PS-K_on0imGZLJi9YNOorLUqqaxJEkY7/)
 6. Optimisation (gradient ascent) [🖥](https://drive.google.com/file/d/1hDknQfrqECkOQeIlfDRzju5rAiVFmFWO/)
 7. Statistical natural language processing [🖥](https://drive.google.com/file/d/1Z38bqW6bq6bop0xfI49KLge0ZzLjPfLn/)
    - RN, chapter 23 – Natural language processing\
      Sections 23.1.0–23.1.4, 23.1.7, 23.6
    - JM, chapter 3 – N-gram language model\
      Sections 3.0–3.6
 8. Digit captioning [🖥](https://drive.google.com/file/d/1MA79-9yKfUX-0iUSjAP9420YkGTBCcAv/)
    - Read programming assignment 4
 9. Classification with neural nets [🖥](https://drive.google.com/file/d/168a4cKw6Bck5imTsFZHeBiieOVyl9Edc/)
    - YouTube animations made by my high-schooler: [vid1](https://youtu.be/UOvPeC8WOt8), [vid2](https://youtu.be/-at7SLoVK_I).
    - PyTorch tensor tutorial notebook. [📓](https://github.com/Atcold/NYU-DLSP20/blob/master/01-tensor_tutorial.ipynb)
    - PyTorch classification notebook. [📓](https://github.com/Atcold/NYU-DLSP21/blob/master/04-spiral_classification.ipynb)
 10. Language sampling and neural NLP [🖥](https://drive.google.com/file/d/1zovfeV7u6TaoY-UdRLbQLzhwjFBLul7V/)
     - JM, chapter 3 – N-gram language model\
       Section 3.4
     - JM, chapter 6 – Vector semantics and embeddings\
       Sections 6.0, 6.3, 6.4, 6.9–6.11
     - RN, chapter 23 – Natural language processing\
       Section 23.1.5
     - RN, chapter 24 – Deep learning for NLP\
       Sections 24.0, 24.1, 24.2.0
 11. Convolutional nets + NB [🖥](https://drive.google.com/file/d/1DjHt30mIWUvh9WRZ-yS1IimyFeTQHaA3/)
     - PyTorch convnet tutorial notebook. [📓](https://github.com/Atcold/NYU-DLSP20/blob/master/06-convnet.ipynb)
 12. Recurrent nets + NB [🖥](https://drive.google.com/file/d/19BURiv9mwY0TYPVnoyfSLJgNYE_trVQu/)
     - PyTorch recurrent net tutorial notebook. [📓](https://github.com/Atcold/NYU-DLSP20/blob/master/09-echo_data.ipynb)
 13. Recurrent nets for NLP and attention [🖥](https://drive.google.com/file/d/1w0em4akxh2M6YCZhBkKOlyKsLDGK7mUu/)
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