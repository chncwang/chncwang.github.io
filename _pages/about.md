---
layout: about
title: about
permalink: /
description: chncwang@gmail.com

profile:
  align: right
  image: prof_pic.jpg
  address: >
    <p>Hangzhou, China</p>

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

**Who am I?**

I'm a master graduate mainly interested in A.I., especially NLP and the A.I. system. Before my graduate school, I had four years of experience as a software engineer.

Especially, I am developing the deep learning library [InsNet](http://github.com/chncwang/insnet) since the year 2017.

**How did I get interested in NLP?**

Long before I get interested in A.I., especially NLP, I got my favorite hobby, which is the game of Go. The rule of Go is straightforward, but it leads to the most complicated game states, which is fascinating.

In 2011, I developed a Go A.I. using MCTS (Monte Carlo tree search) when I was doing my undergraduate thesis. And one year later, I rewrote the program on Github and named it as [FoolGo](http://github.com/chncwang/foolgo). The Go A.I. was an unpopular topic ten years ago, and I had never expected that FoolGo would gain hundreds of stars around the game of AlphaGo vs. Lee Sedol.

Surprised by the fact that MCTS with neural networks can master the game of Go, I quit my job as a Java developer. I went back to college to study A.I. and finally chose NLP as my research field, for NLP is related to my work experience of search server development.

**How do I do NLP research?**

I develop our own deep learning library [InsNet](http://github.com/chncwang/insnet) and use it to conduct NLP research. Specifically, I have conducted three research projects using InsNet as follows:

*Unseen stance detection with adversarial domain generalization.* I proposed the idea of adversarial domain generalization and reproduced the baseline, and then led the first author to conduct experiments and write the paper. The paper [Unseen Stance Detection with Adversarial Domain Generalization](https://arxiv.org/pdf/2010.05471.pdf) is accepted by *IJCNN 2020* as the oral report.

*Cue-word driven open-domain conversation.* I proposed the idea of this work, conducted experiments, and wrote the paper. The paper [Cue-word driven Neural Response Generation with a Shrinking Vocabulary](https://arxiv.org/pdf/2010.04927.pdf) is still a preprint, but my supervisor Dr. Fu really appreciates this work.

*Stance-conditioned open-domain conversation.* This is my master's thesis work. It contains three parts: 1) I used a conversation dataset to train the language models and then finetuned them using thousands of instances with human-annotated stances, resulting in several stance classifiers. Finally, I chose the best classifier to generate pseudo stance labels. 2) I developed the stance-conditioned conversation model and conducted experiments to compare different stance fusion and decoding approaches. Finally, 3) I developed a retrieve-and-refine model and conducted experiments to compare several settings.

**Compared with PyTorch, what's special about InsNet?**

InsNet uses [padding-free dynamic batching](https://insnet.readthedocs.io/en/latest/dynamic_batch.html) making it super easy to build instance-dependent models, such as tree-LSTM and hierarchical Transformer([an example](https://insnet.readthedocs.io/en/latest/getting_started.html#example-of-hierarchical-model)). Besides, it has low GPU memory usage since no padding is needed. I have done preliminary [benchmarks](https://insnet.readthedocs.io/en/latest/benchmark.html).

For the moment, it supports rich operators and prepared NLP modules such as LSTM and Transformer. See [APIs](https://insnet.readthedocs.io/en/latest/reference.html#) for more details.

I believe that deep learning libraries can fundamentally influence researchers' preference for exploring new approaches. Hence, with padding-free dynamic batching, InsNet can encourage researchers to explore more flexible and dynamic models to exploit language structures.

**Why do I want to read a PhD**

I think the best way to maximize the value of my work over the past years is to read a Ph.D. I believe that using language structures, we can design computationally efficient models to parse long sequences. Thus InsNet will be an excellent tool to explore such novel approaches. Besides, InsNet needs to be published as a paper to be promoted to more researchers and even the industry.
