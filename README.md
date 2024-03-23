# Development-of-Variational-Autoencoder-VAE-and-Generative-Adversarial-Network-GAN-
This repository contains the implementation of a Variational Autoencoder (VAE) and a Generative Adversarial Network (GAN) using PyTorch for the generation of airfoil shapes. The models are trained on the UIUCAirfoil Coordinates Database, which includes coordinates for nearly 1,600 airfoils.

## Features
1. **VAE Implementation:** The repository includes a VAE model implemented in PyTorch. The VAE consists of an Encoder, which encodes the input airfoil coordinates into a low-dimensional latent space, and a Decoder, which reconstructs the airfoil coordinates from the latent space.

2. **GAN Implementation:** Additionally, the repository contains a GAN model implemented in PyTorch. The GAN consists of a Generator, which generates synthetic airfoil coordinates from random noise, and a Discriminator, which discriminates between real and fake airfoils.

3. **Training Scripts:** The repository provides training scripts for both the VAE and GAN models. These scripts train the models using the provided airfoil dataset and optimize the models' parameters using appropriate loss functions and optimizers.

4. **Visualization:** The repository includes scripts for visualizing the reconstructed airfoils from the VAE, the synthesized airfoils from both the VAE and GAN, as well as training loss curves for both models.

5. **Helper Functions:** Utilities such as generating random noise and generating labels for the discriminator in the GAN are provided in the `utils.py` file.

## Usage
1. Clone the repository to your local machine:git clone https://github.com/your-username/airfoil-generation-via-VAE-GAN.git

2. Set up your Python environment and install the required dependencies listed in the `requirements.txt` file.

3. Modify hyperparameters, if necessary, in the model files and training scripts to suit your specific requirements.

4. Run the training scripts `train_vae.py` and `train_gan.py` to train the VAE and GAN models, respectively.

5. After training, use the provided visualization scripts to visualize the reconstructed and synthesized airfoils, as well as the training loss curves.

## Contributing
Contributions to this repository are welcome. If you have suggestions for improvements or new features, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

### Carnegie Mellon University (CMU) License
This software is distributed under the terms of the CMU License. See the `LICENSE_CMU` file for details.

## References
- PyTorch VAE implementation: [pytorch/examples/vae](https://github.com/pytorch/examples/tree/master/vae)
- PyTorch GAN implementation: [eriklindernoren/PyTorch-GAN](https://github.com/eriklindernoren/PyTorch-GAN/blob/master/implementations/gan/gan.py)

