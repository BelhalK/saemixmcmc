# saemixmcmc
The code in this repository allows you to run MCMC for PKPD models.
The MCMC kernels are implemented in the SAEMIX R package:

```
@Article{,
author ={E Comets and A Lavenu and M Lavielle},
title ={{SAEMIX}, an {R} version of the {SAEM} algorithm},
journal ={20$^{th}$ meeting of the {P}opulation {A}pproach {G}roup in {E}urope,
Athens, Greece},
type ={Poster},
note ={Abstr 2173},
url ={http://www.page-meeting.org/default.asp?abstract=2173},
year =2011 }
```

It consists of 3 random walk kernels and an independent Metropolis Hastings sampler as developed in:

```
@unpublished{karimi:hal-01958248,
  TITLE = {{f-SAEM: A fast Stochastic Approximation of the EM algorithm for nonlinear mixed effects models}},
  AUTHOR = {Karimi, Belhal and Lavielle, Marc and Moulines, {\'E}ric},
  URL = {https://hal.inria.fr/hal-01958248},
  NOTE = {working paper or preprint},
  YEAR = {2018},
  MONTH = Dec,
  KEYWORDS = {MCMC ; Stochastic approximation ; EM ; mixed effects ; Laplace approximation},
  PDF = {https://hal.inria.fr/hal-01958248/file/fsaem.pdf},
  HAL_ID = {hal-01958248},
  HAL_VERSION = {v1},
}
```