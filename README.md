MNIST2Fashion2Forgery is a research-oriented project exploring the capabilities of Variational Autoencoders (VAE) for cross-domain learning and signature forgery detection. This repository showcases a progressive workflow that:
- Trains a VAE model on the MNIST digit dataset.
- Transfers and adapts the learned representation to the Fashion-MNIST dataset.
- Extends the trained VAE model for a downstream task: fake signature detection using encoded latent features.

Key Highlights
- Dimensionality Reduction using VAEs for compressed feature learning.
- Cross-domain generalization: from handwritten digits to clothing images.
- Signature Forgery Detection using learned latent representations from VAE.

Objectives
- Explore the robustness of VAE-based encoding across visually different domains.
- Investigate how VAEs can be used for feature extraction in forgery detection.
- Apply transfer learning principles from generic datasets (MNIST/Fashion-MNIST) to domain-specific data (signatures).
