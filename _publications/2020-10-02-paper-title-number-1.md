---
title: "A Simple and Effective Baseline for Out-of-Distribution Detection using Abstention"
collection: publications
permalink: /publication/2010-10-02-paper-title-number-1
excerpt: 'Deep neural networks augmented with an extra abstention class and trained on in and out-of-distribution data  show strong out-of-detection performance, often exceeding existing state-of-the-art.'
date: 2010-10-02
venue: 'ICLR 2021 Submission (Under Review)'
paperurl: 'https://openreview.net/forum?id=q_Q9MMGwSQu'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Refraining from confidently predicting when faced with  categories of inputs different from those seen during training is an important requirement for the safe deployment of deep learning systems. While simple to state, this has been  a particularly challenging problem in deep learning, where models often end up making overconfident predictions in such situations. In this work we present a simple, but highly effective approach to deal with out-of-distribution detection that uses the principle of abstention: when encountering a sample from an unseen class, the desired behavior is to abstain from predicting. Our  approach uses a network with an extra abstention class and is trained on a dataset that  is augmented with an uncurated  set that consists of a large number of out-of-distribution (OoD) samples that are assigned the label of the abstention class; the model is then trained to learn an effective discriminator between in and out-of-distribution samples. 

[Paper link](http://academicpages.github.io/files/paper1.pdf)

Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).