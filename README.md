# Generative Vision and Adversarial Robustness

> **Academic Context**: This repository serves as a technical portfolio of advanced laboratories and project implementations completed during my Bachelor's degree. It maps my progression from foundational deep learning baselines to advanced generative synthesis pipelines and modern computer vision security frameworks.

This repository explores the intersection of deep generative synthesis and structural robustness within Computer Vision. The project profiles the architecture, training physics, and latent mechanics of generative models alongside targeted investigations into the privacy boundaries and adversarial vulnerabilities of visual networks.

## Core Themes & Directory Structure

###  Foundational-Architectures
An architectural suite tracking baseline implementations to benchmark optimization dynamics, convergence baselines, and feature map extractions.
* **`MNIST_classification_CNN.ipynb`**: Standard convolutional pipelines evaluating parameter tuning and spatial dimensionality reductions.
* **`ResNet_baseline.ipynb`**: Profiling residual skip-connections to mitigate gradient degradation issues across deep layer topologies.
* **`convolutional_autoencoder_baseline.ipynb`**: Implementation of structural Bottleneck autoencoders evaluating pixel-reconstruction optimization and MSE convergence.
* **`general_autoencoder_baseline.ipynb`**: Standard vanilla autoencoder architecture built to test linear latent space compressions.

###  Generative-Vision-and-Synthesis
Engineering continuous latent spaces and mapping complex, high-dimensional probability distributions to synthesize visual data.
* **`face_generation_vae.ipynb`**: Implementation of a Variational Autoencoder (VAE) optimized over a combined objective function of reconstruction fidelity and structural regularization via Kullback-Leibler (KL) Divergence. Demonstrates continuous latent space arithmetic by manipulating targeted distribution vectors to morph specific visual attributes (e.g., eyeglasses, smiles) on the CelebA dataset.
* **`image_to_image_translation_gan.ipynb`**: Exploring pixel-to-pixel mappings and structural image translations using conditional generative frameworks.
* **`image_colorization_unet.ipynb`**: Leveraging a symmetric U-Net architecture with skip-connections to bridge fine-grained spatial dependencies, re-mapping grayscale visual data to continuous color spaces.
* **`manga_DDPM.ipynb`**: A Denoising Diffusion Probabilistic Model (DDPM) that utilizes Markov chain forward-noising and a structural neural network backbone to iteratively reverse noise into structured anime face distributions.
* **`style_transfer_cnn.ipynb`**: Isolating and recombining style and content representations by computing Gram matrices across intermediate layers of a pre-trained feature extractor.

### Trustworthy-CV-and-Adversarial-Security
A security-first assessment profiling how modern computer vision networks behave under intentional malicious perturbations, visual poisoning, and privacy-extraction attacks.
* **`BackdoorAttack.ipynb`**: Designing and embedding hidden trojan triggers inside model parameters to hijack specific inference classifications.
* **`DeepLeakageFromGradients_MIA.ipynb`**: Demonstrating deep privacy vulnerabilities by intercepting training gradients and performing pixel-perfect visual data reconstructions of private training data.
* **`EvasionAttack.ipynb`**: Crafting imperceptible pixel-level gradient noise to deliberately cross model decision boundaries and force classification failures.
* **`MembershipInferenceAttack.ipynb`**: Exploiting subtle model generalization over-fitting to reliably determine if specific images or faces were present in the training distribution.
* **`NarcissusBackdoorAttack_CIFAR10.ipynb`**: Executing an advanced, clean-label backdoor data poisoning trigger designed to shift internal latent representations maliciously while remaining completely covert.
* **`lenet_mnist_model.pth`**: Trained weight parameters of a LeNet baseline model used to safely deploy, test, and stress-test the visual security scripts.

---

## Technical Stack
* **Frameworks**: PyTorch, Torchvision, Scikit-Image
* **Techniques**: Generative AI, Latent Space Optimization, Diffusion Pipelines, Adversarial Optimization, Gradient Leakage Reconstruction, Privacy-Preserving ML.
