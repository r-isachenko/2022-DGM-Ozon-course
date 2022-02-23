# Deep Generative Models course, OzonMasters, 2022

## Description
The course is devoted to modern generative models (mostly in the application to computer vision). 

We will study the following types of generative models: 
- autoregressive models, 
- latent variable models, 
- normalization flow models, 
- adversarial models,
- diffusion models.

Special attention is paid to the properties of various classes of generative models, their interrelationships, theoretical prerequisites and methods of quality assessment.

The aim of the course is to introduce the student to widely used advanced methods of deep learning.

The course is accompanied by practical tasks that allow you to understand the principles of the considered models.

## Materials

| # | Date | Description | Slides |
|---------|------|-------------|---------|
| 0 | February, 4 | Logistics and intro. | [slides](lectures/intro.pdf) |
| 1 | February, 8 | <b>Lecture:</b> Motivation. Divergence minimization framework. Autoregressive modelling. | [slides](lectures/lecture1/Isachenko2022DeepGenerativeModels1.pdf) |
|  |  | <b>Seminar:</b> Introduction. Density estimation in 1D. MADE theory. | [notebook](seminars/seminar1/1D_histogram.ipynb) |
| 2 | February, 15 | <b>Lecture:</b> Autoregressive models (WaveNet, PixelCNN, PixelCNN++). Bayesian Framework. Latent Variable Models. | [slides](lectures/lecture2/Isachenko2022DeepGenerativeModels2.pdf) |
|  |  | <b>Seminar:</b> MADE practice. PixelCNN implementation hints. Bayesian inference intro, conjugate distributions. | [notebook](seminars/seminar2/MADE.ipynb) |
| 3 | February, 22 | <b>Lecture:</b> Variational lower bound. EM-algorithm, amortized inference. ELBO gradients, reparametrization trick. | [slides](lectures/lecture3/Isachenko2022DeepGenerativeModels3.pdf) |
|  |  | <b>Seminar:</b> Mean field approximation. | TBA |
| 4 | March, 1 | <b>Lecture:</b> Variational Autoencoder (VAE). Posterior collapse and decoder weakening. Tigher ELBO (IWAE). | [slides](lectures/lecture4/Isachenko2022DeepGenerativeModels4.pdf) |
|  |  | <b>Seminar:</b> TBA | TBA |
| 5 | March, 8 | <b>Lecture:</b> Flow models definition. Forward and reverse KL divergence. Residual flows (Planar/Sylvester flows). Linear flows (Glow). | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 6 | March, 15 | <b>Lecture:</b> Autoregressive flows (MAF/IAF/RealNVP). Parallel WaveNet. ELBO surgery. | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 7 | March, 22 | <b>Lecture:</b> ELBO surgery. VampPrior + flow-based VAE prior. Flows-based VAE posterior vs prior. Uniform and variational dequantization. | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 8 | March, 29 | <b>Lecture:</b> Disentanglement learning (beta-VAE, DIP-VAE + summary). Likelihood-free learning. | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 9 | April, 5 | <b>Lecture:</b> GAN theorem. Vanishing gradients and Mode collapse, KL vs JSD. Adversarial Variational Bayes. | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 10 | April, 12 | <b>Lecture:</b> Wasserstein distance. Wasserstein GAN. WGAN-GP. Spectral Normalization GAN. | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 11 | April, 19 | <b>Lecture:</b> f-divergence minimization. GAN evaluation (Inception score, FID, Precision-Recall). | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 12 | April, 26 | <b>Lecture:</b> GAN models (Self-Attention GAN, BigGAN, PGGAN, StyleGAN, truncation trick). Neural ODE. Continuous-in-time NF (FFJORD). | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 13 | May, 3 | <b>Lecture:</b> Discrete VAE (Gumbel-Softmax trick, VQ-VAE, VQ-VAE-2, DALL-E). Diffusion models. | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |
| 14 | May, 17 | <b>Lecture:</b> Diffusion models. | TBA |
|  |  | <b>Seminar:</b> TBA | TBA |

## Homeworks 
| Homework | Date | Deadline | Description | Link |
|---------|------|-------------|--------|-------|
| 1 | February, 13 | February, 27 | <ol><li>Theory (MADE, Mixture of Logistics).</li><li>PixelCNN on MNIST.</li><li>PixelCNN autocomplete and receptive field.</li></ol> | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/hw1.ipynb)<br>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2022-DGM-Ozon-course/blob/main/homeworks/hw1.ipynb) |
| 2 | February, 27 | March, 13 | <ol><li>Theory (log-derivative trick, IWAE theorem).</li><li>VAE on 2D data.</li><li>VAE on CIFAR10.</li></ol> | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/hw2.ipynb)<br>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2022-DGM-Ozon-course/blob/main/homeworks/hw2.ipynb) |
| 3 | March, 13 | March, 27 | <ol><li>Theory (Sylvester flows).</li><li>RealNVP on 2D data.</li><li>RealNVP on CIFAR10.</li></ol> | TBA |
| 4 | March, 27 | April, 10 | <ol><li>Theory (MI in ELBO surgery).</li><li>VAE with AR decoder on MNIST.</li><li>VAE with AR prior on CIFAR10.</li></ol> | TBA |
| 5 | April, 10 | April, 24 | <ol><li>Theory (IW dequantization, LSGAN).</li><li>WGAN/WGAN-GP on 2D data.</li><li>WGAN-GP on CIFAR10.</li></ol> | TBA |
| 6 | April, 24 | May, 8 | <ol><li>Theory (???).</li><li>SN-GAN on CIFAR10.</li><li>FID and Inception Score.</li></ol> | TBA |

## Game rules
- 6 homeworks each of 13 points = **78 points**
- oral cozy exam = **26 points**
- maximum points: 78 + 26 = **104 points**
### Final grade: `floor(relu(#points/8 - 2))`

## Previous episodes
- [MIPT, autumn 2021](https://github.com/r-isachenko/2021-DGM-MIPT-course)
- [OzonMasters, spring 2021](https://github.com/r-isachenko/2021-DGM-Ozon-course)
- [MIPT, autumn 2020](https://github.com/r-isachenko/2020-DGM-MIPT-course)

## Author, feel free to contact :)

- **telegram:** [@roman_isachenko](https://t.me/roman_isachenko)
- **e-mail:** roman.isachenko@phystech.edu
