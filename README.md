# Anime Image Generator with GANs

This repository contains the implementation of a Generative Adversarial Network (GAN) designed to generate anime-style images. The model is trained on the Danbooru2020 dataset, leveraging TensorFlow for building and training the GAN architecture.

## Project Overview

The goal of this project is to experiment with GANs by generating high-quality anime images. This involves using a complex dataset of tagged anime images to train a GAN that can produce new, unique images that maintain the artistic style typical of the dataset.The below representation will provide a holistic view:

## Original Images:
![image](https://github.com/officialkushagragupta/Anime-Face-Generation-GANS-/assets/96885711/b490d54c-924d-454e-9b0c-8581a3945e51)

## Generated Images:
![WhatsApp Image 2024-04-22 at 3 29 52 AM](https://github.com/officialkushagragupta/Anime-Face-Generation-GANS-/assets/96885711/d46c957c-7e4c-4cda-ac74-86161fa6c62c)



## Features

- **Data Preprocessing**: Scripts to clean and normalize the data.
- **Model Training**: Training loops for the discriminator and generator.
- **Evaluation**: Tools to evaluate model performance using metrics like FID scores.
- **Web Deployment**: A Flask application for users to interact with the trained model.

## Installation

To get started with this project, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/anime-image-generator.git
cd anime-image-generator
pip install -r requirements.txt
```

## Usage
To train the model, run:

## bash
```Copy code
python train.py
To launch the web application, run:

bash
Copy code
python app.py
Visit http://localhost:5000 in your browser to interact with the model.
```

## Model Architecture
# Generator
Dense layer, batch normalization, LeakyReLU activations.
Conv2DTranspose layers for upscaling.
Discriminator
Conv2D layers with LeakyReLU activations and dropout.
Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

# Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
# License
Distributed under the MIT License. See LICENSE for more information.

# Contact
Your Name - Kushagra Gupta - kguptaml@gmail.com

## Project Link: https://github.com/officialkushagragupta/Anime-Face-Generation-GANS-
