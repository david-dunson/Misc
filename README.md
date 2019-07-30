## • [JSM 2019: Learning & Exploiting Low-Dimensional Structure in High-Dimensional Data](https://github.com/david-dunson/Misc/blob/master/JSM19-Dunson_vs2.pdf)
Medallion Lecture - July 29th 2019. [Link to slides](https://github.com/david-dunson/Misc/blob/master/JSM19-Dunson_vs2.pdf)

Related repositories:
 - [Efficient-Manifold-Learning-Using-Spherelets](https://github.com/mmukhopadhyay/-Efficient-Manifold-Learning-Using-Spherelets)
 - [Fisher_Gaussian_Kernel_Mixture](https://github.com/david-dunson/Fisher_Gaussian_Kernel_Mixture)
 - [SPAclassifier](https://github.com/david-dunson/SPAclassifier)


## • [NIPS 2018: Scalable Bayesian Inference](https://github.com/david-dunson/Misc/blob/master/ScalableBayes_dunsonNIPS2018.pdf)
Tutorial at NIPS 2018. [Link to slides](https://github.com/david-dunson/Misc/blob/master/ScalableBayes_dunsonNIPS2018.pdf).

Video of the presentation [on Facebook](https://www.facebook.com/nipsfoundation/videos/289885991643586/).

## • [Bayesian variable selection in quantile regression](https://www.researchgate.net/publication/236734631_Bayesian_variable_selection_in_quantile_regression)

### Abstract
In many applications, interest focuses on assessing relationships between predictors and the quantiles of the distribution of a continuous response. For example, in epidemiology studies, cutoffs to define premature delivery have been based on the 10th percentile of the distribution for gesta-tional age at delivery. Using quantile regression, one can assess how this percentile varies with predictors instead of using a pre-defined cutoff. However, there is typically uncer-tainty in which of the many candidate predictors should be included. In order to identify important predictors and to build accurate predictive models, Bayesian methods for variable selection and model averaging are very useful. However, such methods are currently not available for quantile regression. This article develops Bayesian methods for variable selection, with a simple and efficient stochastic search vari-able selection (SSVS) algorithm proposed for posterior computation. This approach can be used for moderately high-dimensional variable selection and can accommodate uncertainty in basis function selection in non-linear and additive quantile regression models. The methods are illustrated using simulated data and an application to the Boston Housing data. 

### Source code and documentation
The model is implemented as R function [`SSVSquantreg`](https://www.rdocumentation.org/packages/MCMCpack/versions/1.4-3/topics/SSVSquantreg), as part of CRAN package [MCMCpack](https://cran.r-project.org/web/packages/MCMCpack/index.html). 
