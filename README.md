# Multilevel-Monte-Carlo-learning

"introductory-example-single.ipynb"
- Single-level algorithm (Table 1.2)

"introductory-example-multi.ipynb"
- Multilevel Monte Carlo learning (Table 1.5) 

"multi-individual-steps.ipynb"
- Multilevel Monte Carlo learning with individual number of trianing steps for each network (Table 2.2)

Examples are given in the folder "example-outputs"

Gerstner et al. "Multilevel Monte Carlo learning." arXiv preprint arXiv:2102.08734 (2021).

https://arxiv.org/abs/2102.08734

In this work, we study the approximation of expected values of functional quantities on the solution of a stochastic differential equation (SDE), where we replace the Monte Carlo estimation with the evaluation of a deep neural network. Once the neural network training is done, the evaluation of the resulting approximating function is computationally highly efficient so that using deep neural networks to replace costly Monte Carlo integration is appealing, e.g., for near real-time computations in quantitative finance. However, the drawback of these nowadays widespread ideas lies in the fact that training a suitable neural network is likely to be prohibitive in terms of computational cost. We address this drawback here by introducing a multilevel approach to the training of deep neural networks. More precisely, we combine the deep learning algorithm introduced by Beck et al. with the idea of multilevel Monte Carlo path simulation of Giles. The idea is to train several neural networks, each having a certain approximation quality and computational complexity, with training data computed from so-called level estimators, introduced by Giles. We show that under certain assumptions, the variance in the training process can be reduced by shifting most of the computational workload to training neural nets at coarse levels where producing the training data sets is comparably cheap, whereas training the neural nets corresponding to the fine levels requires only a limited number of training data sets. We formulate a complexity theorem showing that the multilevel idea can indeed reduce computational complexity. 
