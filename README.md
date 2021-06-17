# torch-utils
Common utilities for for use with PyTorch

## kmeans
Torch implementation of naive k-means.

## twonn
A PyTorch implementation of TwoNN for estimating intrinsic dimensions. 

### Details
Implements the same algorithm as Facco et al. [1] with possibly one exception. The fitting of $`d`$ from

```math
    d = - \frac{\log(1 - F(\mu))}{\log(\mu)}
```

is done with least squares and the denominator as dependent, it is unclear to me how it was done in the paper.


## References
[1] E. Facco, M. d’Errico, A. Rodriguez & A. Laio
    Estimating the intrinsic dimension of datasets by a minimal
    neighborhood information [doi:10.1038/s41598-017-11873-y](https://doi.or/g/10.1038/s41598-017-11873-y)
