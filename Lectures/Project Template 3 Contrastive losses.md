### Project example 3, contrastive losses

Quick references:

- More general: "metric learning" https://gombru.github.io/2019/04/03/ranking_loss/
- https://medium.com/@maksym.bekuzarov/losses-explained-contrastive-loss-f8f57fe32246
- https://proceedings.neurips.cc//paper/2020/hash/d89a66c7c80a29b1bdbab0f2a1a94af8-Abstract.html
- https://github.com/sthalles/SimCLR
- https://paperswithcode.com/paper/a-simple-framework-for-contrastive-learning



Contrastive losses: different way to learn feature representations.

But people still don't understand what is really going on.  Lots of papers focusing on details of how to do it, but not big picture.

Idea: standard classification

- Have data $x$ and label $y$

- Train a deep model to minimize a classsification loss (e.g. margin/cross entropy).
- Model is deep, but can think of it as two layers: features f(x), and linear classifier $h = w*f(x)$. 

Idea contrastive:

- have data $x$, labels $y$ and transformations $T(x) = x'$ which preserve labels.
- learn the feature embedding $f(x)$.  Don't need to use labels directly.
- Instead, want similar data to have similar embeddings!

Note: 

the point is to learn the feature embedding which has a metric / similarity property.

This is totally different from learning a classifier.

Missing Math statement: If you have a feature embedding with similarity embedding, then you can classify!

Idea: formulate and prove this!

- Suggestion:  inputs $x,x'$ similar pairs and $s(x,x') \in [-1,1]$ the cosine similarity.  $S_m = (((x_1,x_1'), y_1), \dots, ((x_m,x_m'), y_m))$
- outputs $f(x)$ such that $f(x')f(x) = y$
-  
