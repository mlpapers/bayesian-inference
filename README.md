# Bayesian Inference
> Remember that using Bayes' Theorem doesn't make you a Bayesian. Quantifying uncertainty with probability makes you a Bayesian. (Michael Betancourt)

### Overview
- Books
  - Free book on Bayesian Inference written in Jupyter Notebooks - [Bayesian Methods for Hackers](https://nbviewer.jupyter.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/tree/master/) *Cam Davidson-Pilon (the main author)*
  - [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/BDA3.pdf) (2020) *Andrew Gelman, John B. Carlin, Hal S. Stern, David B. Dunson, Aki Vehtari, Donald B. Rubin*

### Markov chain Monte Carlo (MCMC)
  - [Introduction to Markov Chain Monte Carlo](http://mcmchandbook.net/HandbookChapter1.pdf) (2011) *Charles Geyer*
- **MH** Metropolis–Hastings algorithm
  - [Equation of State Calculations by Fast Computing Machines](https://people.umass.edu/bvs/The_1953_paper.pdf) (1953) *N. Metropolis, A.W. Rosenbluth, M.N. Rosenbluth, A.H. Teller, E. Teller*
  - [Monte Carlo Sampling Methods Using Markov Chains and Their Applications](http://www2.stat.duke.edu/~scs/Courses/Stat376/Papers/Basic/Hastings1970.pdf) (1970) *W. K. Hastings*
  - [Understanding the Metropolis-Hastings Algorithm](https://www4.stat.ncsu.edu/~wilson/bayes/ChibGreenberg95.pdf) (1995) *S. Chib, E. Greenberg*
- **HMC** Hamiltonian Monte Carlo
  - [MCMC Using Hamiltonian Dynamics](http://www.mcmchandbook.net/HandbookChapter5.pdf) (2011) *Radford M. Neal*
  - [The Geometric Foundations of Hamiltonian Monte Carlo](https://arxiv.org/pdf/1410.5110.pdf) (2014) *Michael Betancourt, Simon Byrne, Sam Livingstone, MarkGirolami*
  - [A Conceptual Introduction to Hamiltonian Monte Carlo](https://arxiv.org/pdf/1701.02434) (2017) *Michael Betancourt*
- **NUTS**
  - [The No-U-Turn Sampler:  Adaptively Setting Path Lengthsin Hamiltonian Monte Carlo](http://www.stat.columbia.edu/~gelman/research/published/nuts.pdf) (2014) *Matthew D. Hoffman, Andrew Gelman*

### Approximate Bayesian Computation (ABC)
  - [Approximate Bayesian Computation in Population Genetics](https://people.eecs.berkeley.edu/~jordan/sail/readings/beaumont-zhang-balding.pdf) (2002) *Mark A. Beaumont, Wenyang Zhang†and, David J. Balding*
  - [Markov chain Monte Carlo without likelihoods](https://people.eecs.berkeley.edu/~jordan/sail/readings/marjoram-etal.pdf) (2003) *Paul Marjoram, John Molitor, Vincent Plagnol, Simon Tavare*
  - [Sequential Monte Carlo without likelihoods](https://people.eecs.berkeley.edu/~jordan/sail/readings/sisson-fan-tanaka.pdf) (2007) *S. A. Sisson, Y. Fan†, Mark M. Tanak*
  - [Non-linear regression models for Approximate Bayesian Computation](https://static.springer.com/sgw/documents/1384032/application/pdf/art%25253A10.1007%25252Fs11222-009-9116-0.pdf) (2009) *Michael G.B. Blum, Olivier François*
  - [Likelihood-free Markov chain Monte Carlo](https://arxiv.org/pdf/1001.2058.pdf) (2010) *Scott A. Sisson, Yanan Fan*
  - [Approximate Bayesian Computation(ABC) in practice](http://membres-timc.imag.fr/Olivier.Francois/CsilleryTREE10.pdf) (2010) *Katalin Csillery, Michael G.B. Blum, Oscar E. Gaggiotti, Olivier Francois*
  - [Hamiltonian ABC](https://deepai.org/publication/hamiltonian-abc)
  - [Reliable ABC model choice via random forests](https://academic.oup.com/bioinformatics/article/32/6/859/1744513) (2016) *Pierre Pudlo, Jean-Michel Marin, Arnaud Estoup, Jean-Marie Cornuet, Mathieu Gautier, Christian P. Robert*

### Variational Inference (VI)
  - [Bayesian parameter estimation viavariational methods](http://www2.stat.duke.edu/~scs/Courses/Stat376/Papers/Variational/JaakkolaJordan2000.pdf) (1999) *T.S. Jaakkola, M.I. Jordan*
  - [The Variational Gaussian Approximation Revisited](http://www0.cs.ucl.ac.uk/staff/C.Archambeau/publ/neco_mo09_web.pdf) (2009) *Manfred Opper, Cedric Archambeau*
  - [Doubly Stochastic Variational Bayes for non-Conjugate Inference](http://proceedings.mlr.press/v32/titsias14.pdf) (2014) *Michalis K. Titsias, Miguel Lazaro-Gredilla*
  - [Variational Inference: A Review for Statisticians](https://arxiv.org/pdf/1601.00670.pdf) (2018) *David M. Blei, Alp Kucukelbir, Jon D. McAuliffe*

### Gaussian processes
  - [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/gpml/chapters/RW.pdf) (2006) *Carl E. Rasmussen, Christopher K. I. Williams*

### Uncertainty calibration
  - [The Well-Calibrated Bayesian](http://fitelson.org/seminar/dawid.pdf) (1982) *A.P. Dawid*
  - [Transforming Classifier Scores into Accurate Multiclass Probability Estimates](https://www.researchgate.net/publication/2571315_Transforming_Classifier_Scores_into_Accurate_Multiclass_Probability_Estimates) (2002) *Bianca Zadrozny, Charles Elkan*
  - [Predicting Good Probabilities With Supervised Learning](https://www.cs.cornell.edu/~alexn/papers/calibration.icml05.crc.rev3.pdf) (2005) *Alexandru Niculescu-Mizil, Rich Caruana*
  - [Nearly-Isotonic Regression](http://www.stat.cmu.edu/~ryantibs/papers/neariso.pdf) (2011) *Ryan J. Tibshirani, Holger Hoefling, Robert Tibshirani*
  - [Binary classifier calibration using an ensemble of piecewise linear regression models](https://www.dbmi.pitt.edu/sites/default/files/Naeini_0.pdf) (2012) *Mahdi Pakdaman Naeini, Gregory F. Cooper*
  - [Beta calibration: a well-founded and easily implemented improvement on logistic calibration for binary classifiers](https://research-information.bris.ac.uk/files/106625004/2017_aistats_beta_calibration_camera_ready.pdf) (2017) *Meelis Kull, Telmo de Menezes e Silva Filho, Peter Flach*
  - [Verified Uncertainty Calibration](https://papers.nips.cc/paper/8635-verified-uncertainty-calibration.pdf) (2019) *Ananya Kumar, Percy Liang, Tengyu Ma*
  - [Improving Regression Uncertainty Estimates with an Empirical Prior](https://arxiv.org/pdf/2005.12496.pdf) (2020) *Eric Zelikman, Christopher Healy*

### Software
  - [Stan](https://mc-stan.org/)
  - BUGS
  - JAGS
- **R**
  - [LaplacesDemon](https://cran.r-project.org/web/packages/LaplacesDemon/index.html)
  - [Greta](https://greta-stats.org/index.html)
  - [Rstanarm](https://cran.r-project.org/web/packages/rstanarm/)
- **Python**
  - [PyMC3](https://github.com/pymc-devs/pymc3), [PyMC4](https://github.com/pymc-devs/pymc4)
  - [Tensorflow Probability](https://github.com/tensorflow/probability)
  - [Edward](http://edwardlib.org/) - now part of Tensorflow Probability
  - [Zhusuan](https://zhusuan.readthedocs.io/en/latest/)
  - [Pyro](https://pyro.ai/)
  - [NumPyro](https://github.com/pyro-ppl/numpyro) - Pyro on JAX
  - [Brancher](https://brancher.org)
  - [Bambi](https://github.com/bambinos/bambi) - PyMC and Stan interface
  - [BRMP](https://github.com/pyro-ppl/brmp) - Pyro interface
- **Julia**
  - [Turing.jl](https://github.com/TuringLang/Turing.jl)
  - [Soss.jl](https://github.com/cscherrer/Soss.jl)
  - [Gen](https://www.gen.dev/)
  - [DynamicPPL](https://github.com/TuringLang/DynamicPPL.jl)
- **Javascript**
  - [WebPPL](https://github.com/probmods/webppl)
- **Web**
  - [StatSim](https://statsim.com/)
