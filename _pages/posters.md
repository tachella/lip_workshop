---
layout: page
permalink: /posters/
title: Posters
description: Accepted poster contributions. Click on an abstract to expand it.
nav: true
nav_order: 5
---

<h2><b>Monday 14 September</b></h2>

<h3>Equivariant Splitting: Self-supervised learning from incomplete data</h3>
<p><b>Victor Sechaud &amp; Jeremy Scanvic</b> (ENS Lyon)</p>
<details>
  <summary>Abstract</summary>
  <p>Self-supervised learning for inverse problems allows to train a reconstruction network from noise and/or incomplete data alone. These methods have the potential of enabling learning-based solutions when obtaining ground-truth references for training is expensive or even impossible. In this paper, we propose a new self-supervised learning strategy devised for the challenging setting where measurements are observed via a single incomplete observation model. We introduce a new definition of equivariance in the context of reconstruction networks, and show that the combination of self-supervised splitting losses and equivariant reconstruction networks results in unbiased estimates of the supervised loss. Through a series of experiments on image inpainting, accelerated magnetic resonance imaging, sparse-view computed tomography, and compressive sensing, we demonstrate that the proposed loss achieves state-of-the-art performance in settings with highly rank-deficient forward models.</p>
</details>

<hr>

<h3>Plug-and-Play methods for reconstructing polarizations of gravitational wave signals</h3>
<p><b>Thomas Sainrat</b> (Laboratoire AstroParticule et Cosmologie, Université Paris Cité, CNRS)</p>
<details>
  <summary>Abstract</summary>
  <p>Plug-and-Play methods have been developed in order to tackle inverse problems with complex priors. They explicitely separate the differentiable likelihood and the regularization, which is likened to a Gaussian denoising task. This denoising tasks can be achieved in a variety of ways, typically using a neural network. We present an application of this type of method to reconstruct the polarizations of gravitational waves given detector data. In particular, we demonstrate it on compact binary coalescences, allowing to recover evidence of relativistic precession within the polarizations.</p>
</details>

<hr>

<h3>Fast dynamic tomographic imaging for material and medical applications</h3>
<p><b>Cyprien Lanneau</b> (ENS Paris Saclay)</p>
<p><i>Abstract: TBA</i></p>

<hr>

<h3>Joint choice for the acquisition and reconstruction operator for single pixel camera</h3>
<p><b>Joseph Arnold</b> (CREATIS, INSA Lyon)</p>
<p><i>Abstract: TBA</i></p>

<hr>

<h3>GAN-Based Generation and Super-Resolution of Multivariate Multifractal Textures</h3>
<p><b>Jhonatan Ancco</b> (ENS Lyon)</p>
<details>
  <summary>Abstract</summary>
  <p>Multivariate scale-free texture images are nowadays central in numerous modern applications very different in natures. A common challenging issue consists in being able to generate such multivariate textures at any arbitrary size, from a learning set of (possibly much) smaller size. Parametric model often turn too restrictive for the generation of realistic textures, thus prompting for neural network training based generation. While a number neural network approaches propose generation at sizes larger than training, they do not explicitly seek to reproduce multiscale or scale-free statistics in textures and rely on perceptual assessment. The present combines convolutional Wasserstein-GAN architectures with self-attention layers to permit to generate textures of arbitrary size that focus on reproducing multiscale statistics. Quantitative assessment conducted from paradigmic multifractal textures show that the proposed architecture turns able to generate textures with accurate statistics for size \(16 \times 16\) larger than originals.</p>
</details>

<hr>

<h3>SPECT with a Compton camera: image reconstruction challenges and deep learning perspectives</h3>
<p><b>Leo Milliat</b> (CREATIS, INSA Lyon)</p>
<details>
  <summary>Abstract</summary>
  <p>Compton cameras are gamma-ray imaging systems based on Compton kinematics. Initially used for astronomy applications, Compton camera is becoming an emergent technology in Single Photon Emission Computed Tomography (SPECT). Compared to classical SPECT devices with mechanical collimation, Compton camera imaging offers potential advantages such as higher sensitivity and the capability to detect a wide range of photon energies. These characteristics pave the way for monitoring emerging targeted radionuclide therapies. However, both the camera and the reconstruction algorithms, need to be further optimized to meet the requirements for clinical applications, particularly for diagnosis and theragnosis purposes.</p>
</details>

<hr>

<h3>Implicit Neural Deblurring: A Self-Supervised Multi-Scale Framework</h3>
<p><b>Omar Zribi</b> (CREATIS, INSA Lyon)</p>
<details>
  <summary>Abstract</summary>
  <p>Blind image deblurring remains a fundamental ill-posed inverse problem, where both the latent sharp image and the unknown blur kernel must be recovered from a single blurred observation, a challenge particularly acute in pathology imaging where ground-truth data are rarely available. In this paper, we present a self-supervised blind deblurring approach based on implicit neural representations (INRs) that addresses these limitations. By parameterising the sharp image and the blur kernel as coordinate-based neural networks, our method goes beyond image discretization and enables flexible, resolution-free optimisation. The key to our success lies in a coarse-to-fine multi-scale training scheme that guides the optimisation from low to high frequencies. This is complemented by ℓ2 regularisation on the kernel and total variation (TV) regularisation on the image, which jointly promote smooth, compact kernels and edge-preserving sharp reconstructions. Extensive experiments on fluorescence microscopy and transmission electron microscopy demonstrate that our method achieves competitive performance compared to state-of-the-art self-supervised techniques.</p>
</details>

<hr>

<h3>Training with noisy labels &mdash; a functional gradient perspective</h3>
<p><b>Manon Verbockhaven</b> (ENS Lyon)</p>
<details>
  <summary>Abstract</summary>
  <p>In supervised machine learning, models are trained on a finite dataset of independent draws of some random variables \(\left(X, Y\right)\) on which we suppose a statistic model of the form \(Y \sim y^*(X) + \sigma\epsilon\) where \(\epsilon\sim \mathcal{E}\) is a noise term, \(\sigma\) is the level of noise and \(y^*\) is a deterministic function of \(X\). In regression (\(Y\in \mathbb{R}^q\)), the noise is understood as a physical phenomenon, while in classification (\(Y\in \Delta^q\)), it can either stem from a misclassification error or, as introduced by the student-teacher networks, from the interpretation of the cross entropy loss as an approximation of the Kullback-Leibler divergence with the caricatural density defined by the one-hot encoding \(Y\). In both cases, when the variable \(X\) lives in a high-dimensional space, the dataset size is often insufficient to cancel the impact of the noise in the training dynamic, leading to a generalization gap in performance. In this work, we take a functional perspective on the optimization criterion \(L\) as an application from a function class \(\mathcal{F}\) to \(\mathbb{R}^+\) and define its functional derivative \(\nabla_f L\). For many usual criteria \(L\), we show that the application \(\nabla_f L\) satisfies a linearity property which grasps the impact of the noise on the training dynamic and that allows simple Monte Carlo estimates of it.</p>
  <p>From this theoretical analysis and for any prior on \(\epsilon\), we propose an estimate of \(\sigma\) and a hard thresholding strategy on the gradient descent algorithm that is model and parameter-dependent. We show empirically, on regression and classification tasks, that this strategy mitigates the effect of the noise on the training dynamic while preserving the final performance of the model.</p>
</details>

<hr>

<h2><b>Tuesday 15 September</b></h2>

<h3>Self-supervised Bayesian imaging with equivariant VAEs</h3>
<p><b>Bernardin Tamo Amougou</b> (Heriot-Watt University)</p>
<details>
  <summary>Abstract</summary>
  <p>Imaging inverse problems are often severely ill-posed, making uncertainty quantification essential for the reliable use of reconstructed images in scientific and medical applications. Deep generative models provide expressive data-driven priors, but they typically require large collections of clean training images or computationally expensive iterative posterior sampling procedures. Recent self-supervised generative methods reduce the need for ground-truth images by learning from corrupted measurements, but often rely on measurement diversity, such as multiple degradation operators or random masks, to constrain components of the signal that are unobserved by any single operator. This assumption is restrictive in many acquisition protocols where all measurements are produced by a fixed forward operator. We introduce the Equivariant Self-Supervised Variational Autoencoder (ESS-VAE), a measurement-space latent-variable framework for self-supervised Bayesian imaging in the fixed-operator regime. ESS-VAE uses the noiseless measurement \(Y_0=AX\) as a physically meaningful latent variable and learns a reconstruction map from noisy measurements only. The method combines a SURE-based measurement-consistency objective with robust equivariant constraints, which use signal symmetries to induce virtual sensing geometries and constrain nullspace components without requiring operator diversity. First- and second-order Tweedie identities are then applied in measurement space to construct a local Gaussian approximation of \(p(Y_0\mid Y=y)\). Posterior image samples are generated by a non-iterative equivariant push-forward sampler requiring two neural function evaluations per sample. We validate ESS-VAE on structured data, natural image inpainting, and sparse-angle computed tomography. Across these settings, ESS-VAE achieves reconstruction accuracy competitive with supervised references, remains effective in fixed-operator regimes where measurement-diversity methods degrade, and provides empirically well-calibrated sample-based uncertainty estimates while substantially reducing the cost of generating Monte Carlo posterior samples compared with iterative diffusion-based baselines.</p>
</details>

<hr>

<h3>From Convex Poisson Renewal Models to Negative-Binomial Extensions: A Variational Framework for Robust Epidemic Inference</h3>
<p><b>Giuseppe Petrillo</b> (ENS Lyon)</p>
<details>
  <summary>Abstract</summary>
  <p>Renewal models have become a central tool for the estimation of time-varying reproduction numbers from epidemic incidence data. Several recent approaches formulate the inference problem within a convex optimization framework by combining a Poisson observation model, temporal regularization of the reproduction number, and robust correction terms accounting for reporting anomalies and outliers. The resulting estimators benefit from strong theoretical guarantees, numerical stability, and efficient optimization algorithms. In this work, we revisit the mathematical structure underlying these convex Poisson renewal formulations and investigate their extension to more realistic observation models. While the Poisson assumption implies equality between the conditional mean and variance of incidence counts, epidemic data frequently exhibit substantial overdispersion arising from heterogeneous transmission, superspreading events, reporting fluctuations, and aggregation effects. To address this limitation, we consider a negative-binomial observation model while preserving the robust additive-outlier structure of the original formulation. We show that the resulting negative-binomial objective is generally non-convex and characterize explicitly the region of local convexity in parameter space. Despite the loss of global convexity, we prove that the objective admits a natural difference-of-convex decomposition. These results establish a mathematical bridge between existing convex renewal methods and more flexible overdispersed epidemic models.</p>
</details>

<hr>

<h3>Noise2Ghost: Self-supervised deep convolutional reconstruction for ghost imaging</h3>
<p><b>Nicola Viganò</b> (UGA, CEA, Grenoble)</p>
<details>
  <summary>Abstract</summary>
  <p>We present a new self-supervised deep-learning-based Ghost Imaging reconstruction method, which provides unparalleled reconstruction performance for noisy acquisitions among unsupervised methods. Self-supervision removes the need for clean reference data while offering strong noise reduction. This provides the necessary tools for addressing signal-to-noise ratio concerns for GI acquisitions in emerging and cutting-edge low-light GI scenarios.</p>
</details>

<hr>

<h3>Robust Multifractal Analysis for Incomplete Data</h3>
<p><b>Lorena León</b> (Université Grenoble Alpes / Gipsa-lab)</p>
<details>
  <summary>Abstract</summary>
  <p>We present a Bayesian approach for robust multifractal analysis of multivariate data with missing samples. Using a debiased Whittle approximation, the proposed method enables accurate and computationally efficient estimation of multifractality parameters from incomplete data. Its performance is demonstrated through Monte Carlo simulations and an application to financial data.</p>
</details>

<hr>

<h3>Unrolled relaxed algorithm for 3D SPECT reconstruction</h3>
<p><b>Corentin Constanza</b> (CREATIS)</p>
<details>
  <summary>Abstract</summary>
  <p>We propose an unrolled BSREM framework for 3D SPECT reconstruction, incorporating a learned regularization gradient and trained with Jacobian-Free Unrolling (JFU). We investigate the impact of relaxation strategies and show that JFU improves training stability and reconstruction performance. Interestingly, JFU and relaxation exhibit similar stabilizing effects on the unrolled training process, suggesting that JFU may intrinsically act as a form of relaxation. However, JFU achieves this stabilization without the performance loss associated with strong explicit relaxation, leading to better reconstruction performance with weak or no relaxation.</p>
</details>

<hr>

<h3>Deep Lightweight Unrolled Network for High Dynamic Range Modulo Imaging</h3>
<p><b>Brayan Monroy</b> (Universidad Industrial de Santander)</p>
<p><i>Abstract: TBA</i></p>

<hr>

<h3>LATINOs: zero-shot latent distilled generative image and video restoration algorithms</h3>
<p><b>Alessio Spagnoletti</b> (Université Paris-Cité)</p>
<details>
  <summary>Abstract</summary>
  <p>The poster presents LATINOs, a family of zero-shot image and video restoration methods that combine distilled latent consistency-model priors with explicit data-fidelity corrections. Unlike diffusion-based approaches requiring many denoising steps and repeated backpropagation through the measurement model, LATINOs operate in only a few function evaluations using proximal physics updates. LATINO-PRO additionally performs prompt self-calibration through marginal maximum-likelihood estimation, while LVTINO combines video and image consistency priors with spatio-temporal total variation to preserve both temporal coherence and fine spatial detail. Experiments on challenging deblurring and super-resolution tasks show competitive perceptual and reconstruction quality at substantially reduced computational cost.</p>
</details>
