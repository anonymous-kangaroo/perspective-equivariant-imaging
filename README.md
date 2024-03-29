# Perspective-Equivariant Imaging: an Unsupervised Framework for Multispectral Pansharpening

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anonymous-kangaroo/perspective-equivariant-imaging)
[Demo webpage](https://anonymous-kangaroo.github.io/perspective-equivariant-imaging) | [Demo notebook](demo.ipynb)

**Authors**: Anonymous

**Abstract**: Ill-posed image reconstruction problems appear in many scenarios such as remote sensing, where obtaining high quality images is crucial for environmental monitoring, disaster management and urban planning. Deep learning has seen great success in overcoming the limitations of traditional methods. However, these inverse problems rarely come with ground truth data, highlighting the importance of unsupervised learning from partial and noisy measurements alone. We propose _perspective-equivariant imaging_ (EI), a framework that leverages perspective variability in optical camera-based imaging systems, such as satellites or handheld cameras, to recover information lost in ill-posed optical camera imaging problems. This extends previous EI work to include a much richer non-linear class of group transforms and is shown to be an excellent prior for satellite and urban image data, where perspective-EI achieves state-of-the-art results in multispectral pansharpening, outperforming other unsupervised methods in the literature.

## 1. Results

![](img/eval_spacenet_pansharpen_noiseless.png)