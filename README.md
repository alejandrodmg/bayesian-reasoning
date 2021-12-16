Some examples of reasoning in Knowledge Representation.

## Inference with Bayesian Networks

![Bayesian Network](img/BayesNet.png)

Example:

What is the probability that there isn't any traffic, and fossil fuel consumption is above the average, and global warming indicators aren't showing a red flag, and charging stations using renewal energy are running out of battery, and there's a new AI job posted, and no one of our community is getting employed for a new AI role. 

<img src="https://render.githubusercontent.com/render/math?math=P(T, FF, GW, RE, AI, E) = P(T) \cdot P(FF|T) \cdot P(GW|FF) \cdot P(RE|T) \cdot P(AI|RE) \cdot P(AI|GW, RE) \cdot P(E)">

<img src="https://render.githubusercontent.com/render/math?math=P(T=false, FF=true, GW=false, RE=true, AI=true, E=false) = = (1 - 0.47) \cdot 0.23 \cdot (1 - 0.63) \cdot 0.52 \cdot 0.36 \cdot (1 - 0.10) = 0.0075">

Using the above definition of our world and the Join Probability Distribution (JPD) we can say that there's a tiny 0.75% probability of all these events happening together.

## Learning with Naive Bayes

Analysis of Naive Bayes from a probabilistic perspective on famous datasets Breast Cancer Wisconsin originally created by Dr. William H. Wolberg. and Tic-Tac-Toe Endgame by David W. Aha.

- Conditional independence 
- Laplace Smoothing
- Multinomial vs Bernoulli distribution




