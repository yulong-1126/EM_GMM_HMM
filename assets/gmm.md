A GMM is a weighted sum of M components Gaussian densities. In single Gaussians, one can use Maximum Likelihood Estimate (MLE) to identify the optimal parameters. 

However, when we mix Gaussians, the likelihood does not have a proper analytical solution. EM algorithm is an interative algorithm which supposes the existence of a latent variable telling us to which Gaussian each point belongs to. Knowing this information, we are able to derive the parameters of each Gaussian. EM is an interative approach, since at each steap, it tries to update the parameters in order to maximize the likelihood, and eventually finds the maximum likelihood. 

EM identifies local optimum, and is usually initialized with a k-Means approach. Below, we present data generated from Gaussian Mixture Models in 1, 2 and 3 dimensions.