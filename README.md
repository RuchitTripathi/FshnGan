# FshnGan Project

## Overview

This project implements a Generative Adversarial Network (GAN) using TensorFlow to generate synthetic images resembling the Fashion MNIST dataset. The GAN consists of a generator and a discriminator trained in an adversarial manner to produce realistic fashion images.

## Project Structure

The project is organized as follows:

- **1. Import Dependencies and Data:** Install necessary libraries, import TensorFlow, and load the Fashion MNIST dataset.

- **2. Visualize Data and Build Dataset:** Visualize a few samples from the dataset, perform data transformations, and build a pipeline for training.

- **3. Build Neural Network:**
    - **3.1 Import Modelling Components:** Import essential components for building the generator and discriminator.
    - **3.2 Build Generator:** Define the architecture of the generator model.
    - **3.3 Build Discriminator:** Define the architecture of the discriminator model.

- **4. Construct Training Loop:**
    - **4.1 Setup Losses and Optimizers:** Define loss functions and optimizers.
    - **4.2 Build Subclassed Model:** Subclass a model for training the GAN.
    - **4.3 Build Callback:** Implement a callback to monitor and save generated images during training.
    - **4.3 Train:** Train the GAN model using the Fashion MNIST dataset.
    - **4.4 Review Performance:** Plot and review the training loss curves.

- **5. Test Out the Generator:**
    - **5.1 Generate Images:** Generate sample images using the trained generator.
    - **5.2 Save the Model:** Save the generator and discriminator models.

## Usage

1. Ensure you have the required dependencies installed by running:

   ```bash
   pip install tensorflow tensorflow-gpu matplotlib tensorflow-datasets ipywidgets
   ```

2. Execute the provided code in a Jupyter Notebook or Python environment.

3. Review the generated images during training in the 'images' directory.

4. Customize hyperparameters, model architectures, and other settings as needed.

## Results

The trained GAN produces synthetic fashion images that closely resemble the Fashion MNIST dataset. Check the 'images' directory for visualizations.

## Notes

- This implementation assumes a TensorFlow environment and requires GPU support for optimal training performance.

- Experiment with hyperparameters, model architectures, and training duration for better results.

## Author

 Ruchit 

## License

This project is licensed under the [MIT License](LICENSE).
```
