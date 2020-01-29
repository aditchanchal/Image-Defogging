# Image-Defogging
Image Defogging model using CNN

# Abstract
I have implemented a daytime image dehazing method that finds the transmittance at each patch (and
subsequently at each pixel) by comparing the dehazed version of the patch with the hazy one. Now, this
comparison is performed by the module called CNN based patch quality comparator.

I(x) = J(x)t + (1 - t)A

where,

* I(x) is the observed intensity
* J(x) is the intensity of light coming from the scene objects and before getting scattered
* t(x) is the scene transmittance denoting the amount of light that reaches the observer after getting scattered
* A denotes the global environmental illumination

# Results
* SSIM (%) = 96.9
