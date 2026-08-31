---
layout: page
permalink: /talks/
title: Talks
description: Titles and abstracts of the invited talks. Click on an abstract to expand it.
nav: true
nav_order: 4
---

<h3>Marcelo Pereyra (Heriot-Watt University)</h3>
<p><b>Physics-Grounded Foundation Models for Generative Computational Imaging</b></p>
<details>
  <summary>Abstract</summary>
  <p>This talk presents a mathematical and computational framework for physics-grounded foundation models in Bayesian computational imaging, integrating physical forward models with state-of-the-art deep generative models such as distilled denoising diffusion models and flow maps. The resulting models are modular and interpretable, with layers that map directly to statistical signal priors and data likelihoods. Likelihood layers are designed for flexibility: forward model parameters are specified at inference time, enabling zero-shot deployment with pre-trained generative priors, or alternatively supervised fine-tuning for greater computational efficiency. The latter is achieved through consistency model self-distillation, delivering excellent generative performance in as few as two/three steps while retaining full forward model flexibility and physical consistency. The framework is validated through extensive experiments in image and video restoration, supported by rigorous mathematical theory. We conclude by discussing self-supervised fine-tuning of foundation models directly from measurement data, without ground truth.</p>
  <p>This talk draws on a series of recent works in physics-grounded generative AI for Bayesian imaging: a zero-shot framework using a distilled latent Stable Diffusion XL model trained on five billion images (arXiv:2503.12615, ICCV 2025); its extension to generative video restoration (arXiv:2510.01339, ICLR 2026); a pixel-based approach integrating diffusion models with deep unfolding and diffusion distillation (arXiv:2507.02686, TMLR 2025); and a self-supervised framework for learning diffusion models directly from noisy and incomplete measurements (arXiv:2510.11964, ICLM 2026).</p>
</details>

<hr>

<h3>Florence Forbes (Inria Grenoble)</h3>
<p><b>Scalable Bayesian Experimental Design with Diffusions</b></p>
<details>
  <summary>Abstract</summary>
  <p>Bayesian Optimal Experimental Design (BOED) is a powerful tool to reduce the cost of running a sequence of experiments. When based on the Expected Information Gain (EIG), design optimization corresponds to the maximization of some intractable expected contrast between prior and posterior distributions. Scaling this maximization to high dimensional and complex settings has been an issue due to BOED inherent computational complexity. In this work, we introduce a pooled posterior distribution with cost-effective sampling properties and provide a tractable access to the EIG contrast maximization via a new EIG gradient expression. Diffusion-based samplers are used to compute the dynamics of the pooled posterior and ideas from bi-level optimization are leveraged to derive an efficient joint sampling-optimization loop. The resulting efficiency gain allows to extend BOED to the well-tested generative capabilities of diffusion models. By incorporating generative models into the BOED framework, we expand its scope and its use in scenarios that were previously impractical. Numerical experiments and comparison with state-of-the-art methods show the potential of the approach. An illustration on a real-world MRI application in medical imaging is also given.</p>
  <p><i>Joint work with Jacopo Iollo, Christophe Henkele and Pierre Alliez.</i></p>
</details>

<hr>

<h3>Rémi Gribonval (Inria Lyon)</h3>
<p><b>Training dynamics of ReLU Networks: a Path-lifting Perspective</b></p>
<details>
  <summary>Abstract</summary>
  <p>Can we hope to decipher the role of the well-known rescaling symmetries of ReLU networks parameterizations in their training dynamics? The talk will explore recent advances in this direction that exploit the path-lifting, a rescaling-invariant polynomial representation of the parameters of general ReLU networks. Despite its combinatorial dimension, the path-lifting turns out to be not only a convenient mathematical analysis tool: it also gives rise to a computational toolbox to reveal useful properties of the function corresponding to a ReLU network, from Lipschitz regularity to convexity. As we will see, the path-lifting viewpoint also leads to simple modifications of gradient descent that accelerate network training.</p>
</details>

<hr>

<h3>Rich Baraniuk (Rice University)</h3>
<p><b>Learning from Collapse: Self-Consuming Loops in AI and the Humans Who Feed Them</b></p>
<details>
  <summary>Abstract</summary>
  <p>Training generative models on synthetic data creates feedback loops that amplify artifacts and bias and degrade quality and diversity, a phenomenon known as model collapse or MADness. This talk makes two turns. First, we show how to learn from collapse: the way a model degrades under self-training can tell us how to improve it. Second, we ask whether collapse might reach beyond models: fresh real data can stabilize self-consuming loops, but generative AI is beginning to reshape human language, ideas, and attention. Humans may no longer be outside the loop.</p>
</details>

<hr>

<h3>Mike Davies (University of Edinburgh)</h3>
<p><b>TBA</b></p>

<hr>

<h3>Caroline Chaux (CNRS &amp; Aix Marseille Université)</h3>
<p><b>TBA</b></p>

<hr>

<h3>Julien Mairal (Inria Grenoble)</h3>
<p><b>Machine learning and optimization for scientific imaging</b></p>
<details>
  <summary>Abstract</summary>
  <p>Reconstruction in scientific imaging means solving large-scale ill-posed inverse problems, where a physical forward operator is paired with a regularizer encoding prior knowledge. We will first present a few problems where hybrid approaches combining physical models of image formation and deep learning are highly successful. We will then address the choice of estimator, as perceptual quality does not align with criteria such as the mean squared error, whose minimizers are over-smoothed. This motivates targeting the maximum a posteriori estimate, which requires the proximal operator of the negative log-prior --- an intractable object that practitioners routinely replace by a pretrained denoiser. We will show that a simple algorithm, close to several used in practice, provably converges to this operator under a log-concavity assumption, and can be read as gradient descent on smoothed approximations of the proximal objective, yielding rates and guarantees for a class of previously heuristic methods.</p>
</details>
