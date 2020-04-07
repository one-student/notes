## Variational Bayes

Variational Laplace if all variables Normal (often called **Laplace assumption**).


## Bayesian model comparison
In statistics, the use of **[Bayse factors](https://en.wikipedia.org/wiki/Bayes_factor)** is a Bayesian alternative to classical hypothesis testing. ***Bayesian model comparison*** is a method for the [selection](https://en.wikipedia.org/wiki/Model_selection) of the best statistical model based on Bayes factors. If _M<sub>1,2</sub>_ stand for two models with parameters _θ<sub>1,2</sub>_ and _D_ for a set of data, then $\frac{P(M|D)P(M)}{P(D)}$ and the Bayes factor K is given by

$$K=\frac{P(D|M_1)}{P(D|M_2)}=\frac{E_{P(\theta_1|M_1)}[P(D|\theta_1,M_1)]}{E_{P(\theta_2|M_2)}[P(D|\theta_2,M_2)]}=\frac{P(M_1|D)P(M_1)}{P(M_2|D)P(M_2)}$$

- A value of $K > 1$ means that $M_1$ is more strongly supported by the data under consideration than $M_2$, and the opposite for $K < 1$. $K$ between $10^0-10^{1/2}$, result barely worth mentioning, between $10^{1/2}-10^1$ substantial, ....., $> 10^2$ decisive! Check [Wikipedia](https://en.wikipedia.org/wiki/Bayes_factor#Interpretation).
- See [Wikipedia](https://en.wikipedia.org/wiki/Bayes_factor#Example) for an easy example.

**NOTES:** When the two models are equally probable a priori (the priors are equal) the Bayes factor is equal to the ratio of the posterior probabilities of M1 and M2. This method does not depend on a specific set of parameters and integrates through all! It has a penalty for complicated structures so it's good against overfitting.



## Criteria for model selection

* Akaike information criterion (**AIC**), a measure of the goodness fit of an estimated statistical model
* **Bayes factor**
* Bayesian (or Schwarz) information criterion (**BIC**), a statistical criterion for model selection
* **Cross-validation**
* Deviance information criterion (**DIC**), another Bayesian oriented model selection criterion.
* For more check [Wikipedia](https://en.wikipedia.org/wiki/Model_selection) ...

## Bayesian model reduction
Links: [Wikipedia](https://en.wikipedia.org/wiki/Bayesian_model_reduction), [ArXiv tutorial by Karl](https://arxiv.org/ftp/arxiv/papers/1805/1805.07092.pdf)
- Originally referred to (by Karl) as post-hoc Bayesian model selection.

It is a method for computing the evidence and posterior over the parameters of Bayesian models that differ in their priors. A full model is fitted to data using standard approaches. Hypotheses are then tested by defining one or more 'reduced' models with alternative (and usually more restrictive) priors, which usually – in the limit – switch off certain parameters. The evidence and parameters of the reduced models can then be computed from the evidence and estimated (posterior) parameters of the full model using Bayesian model reduction. If the priors and posteriors are normally distributed, then there is an analytic solution which can be computed rapidly.

## Variational Laplace
Used in DCM usually..

## Dynamic causal modelling
Links: [Wikipedia](https://en.wikipedia.org/wiki/Dynamic_causal_modeling), [Scholarpedia](http://www.scholarpedia.org/article/Dynamic_causal_modeling)

## Statistical parametric mapping
Links: [Wikipedia](https://en.wikipedia.org/wiki/Statistical_parametric_mapping), [FIL's link](#)



Inline-style: ![alt text](https://url "Logo")
Reference-style:  ![alt text][logo]
[logo]: https://url "Logo"
Local file (same folder as markdown): ![alt text](stats/aa.jpg)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA3OTY2MzIyMiwtMjA1MzQ0MjU2Nyw3Mz
MxOTU3MjMsOTc3MTY3MzM3LDEzMzc1OTgxMjQsMjI2NTIwODg0
XX0=
-->