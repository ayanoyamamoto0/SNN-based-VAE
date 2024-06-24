# :brain: SNN based VAE: Project Overview
* Preprocessed EEG data from Participant 1 from the DEAP dataset and converted them into spatially preserved EEG topographic maps
* From the 307,200 topographic maps, randomly downsampled the dataset into sets of 10,000, 20,000, 40,000, 80,000, and 160,000 images
* Built an SNN-based variational autoencoder for latent space interpretation and reconstruction of the topographic maps
* Compared it with an ANN-variational autoencoder using MSE, MAE, and SSIM as evaluation metrics

## Reference
The code in this project is adapted from:

Kamata, H., Mukuta, Y., & Harada, T. (2022, June). *Fully spiking variational autoencoder*. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 36, No. 6, pp. 7059-7067). [https://doi.org/10.1609/aaai.v36i6.20665](https://doi.org/10.1609/aaai.v36i6.20665 )

Github: [https://github.com/kamata1729/FullySpikingVAE](https://github.com/kamata1729/FullySpikingVAE)

## Other Code and Resources Used
* Environment: Python kernel on Google Colab
* Python Version: 3.10.12
* The DEAP dataset: [https://www.eecs.qmul.ac.uk/mmv/datasets/deap/](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/)
