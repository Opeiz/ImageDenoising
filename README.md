# ImageDenoising

## Visual Comparison
Repo dedicated for the visual comparison of Denoising classic method like

- Gaussian filter
- Bilateral filter
- Non-Local Means filter
- Anisotropic difussion filter
- K-SVD

## Numerical Comparison
For the numerical comparison, we use:

- PSNR, Peak Signal noise ratio
- SSIM, Structural Similarity
- MSE, Mean Square error

# Usage

For using the repo, go directly to:
```
K-SVD-Comparison.ipynb
```

# Issues
There's no good documentation about using k-svd in python, I found a [yspMing repo](https://github.com/yspMing/K-SVD-simple-implementation) but didnt work.

That's why the k-svd images used in the jupyter notebook are from the IPOL C++ implementation.

# Links
[IPOL Paper with K-SVD C++ Implementation](https://ipolcore.ipol.im/demo/clientApp/demo.html?id=58&key=11B678CB731EC80E602F6BA634886C2E)