# RStan + Binder

**IMPORTANT:** Until the MyBinder service upgrades to Ubuntu 22 (soon!) you'll have to build the container yourself using [repo2docker](https://repo2docker.readthedocs.io/en/latest/install.html):

```
python3 -m pip install jupyter-repo2docker
git clone https://github.com/julianpistorius/RStan-Binder.git
cd RStan-Binder
repo2docker --Repo2Docker.base_image=docker.io/library/buildpack-deps:jammy .
```

---

You can try it with the following buttons (once MyBinder uses Ubuntu 22 - see above):

Jupyter+R: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/julianpistorius/RStan-Binder/master?filepath=README.md)

RStudio: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/julianpistorius/RStan-Binder/master?urlpath=rstudio)

## What is Stan?
**[Stan](http://mc-stan.org/)** is an probabilistic programming language. Probabilistic programming languages are languages designed to describe probabilistic models as well as perform the necessary inferential computation.
> Carpenter, Bob, et al. "Stan: A probabilistic programming language" in Journal of Statistical Software (2017). DOI [10.18637/jss.v076.i01](http://dx.doi.org/10.18637/jss.v076.i01)

## Examples Notebooks
1. Bernoulli ([notebook](examples/bernoulli.ipynb) | [model](examples/bernoulli.stan))
2. Linear Regression ([notebook](examples/linear.ipynb) | [model](examples/linear.stan))
2. Seven Scientists ([notebook](examples/7scientists.ipynb) | [model](examples/7scientists.stan))

## Further Resources
* [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/) by Andrew Gelman et al. ([R](https://github.com/avehtari/BDA_R_demos) or [Python](https://github.com/avehtari/BDA_py_demos))
* Bayesian Cognitive Modeling ([link](https://bayesmodels.com/))
* Probabilistic Programming & Bayesian Methods for Hackers ([link](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/))
* Bayesian Analysis for the Social Sciences by Simon Jackman ([link](https://www.wiley.com/en-us/Bayesian+Analysis+for+the+Social+Sciences-p-9780470011546))


## Other Probabilistic Programming Languages
* PyMC3 ([link](http://docs.pymc.io/))
* FACTORIE ([link](http://factorie.cs.umass.edu/))
* Turing ([link](https://github.com/TuringLang/Turing.jl))
* Edward ([link](https://github.com/blei-lab/edward))
* ... and [many more](https://en.wikipedia.org/wiki/Probabilistic_programming_language#List_of_probabilistic_programming_languages)

Furthermore, of historical relevance are [BUGS](https://www.mrc-bsu.cam.ac.uk/software/bugs/) and [JAGS](http://mcmc-jags.sourceforge.net/). 


---

Funded by the German Research Foundation (DFG).
FKZ/project number:
[324867496](https://gepris.dfg.de/gepris/projekt/324867496?context=projekt&task=showDetail&id=324867496&).
