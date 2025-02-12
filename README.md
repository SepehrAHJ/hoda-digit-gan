
# Persian Handwritten Digits Generation using GAN

## Description

This project implements a Generative Adversarial Network (GAN) to generate handwritten Persian digits using the Hoda dataset. The goal is to train a generator to create realistic digit images that mimic the handwriting style of Persian numbers. The project includes a generator and discriminator model, both utilizing batch normalization for improved stability during training.

## Objectives

- Train a GAN using the Hoda dataset to generate realistic Persian handwritten digits.
- Implement an improved Generator and Discriminator with Batch Normalization for better model performance.
- Experiment with different network architectures and hyperparameters.
- Generate fake images and evaluate the quality of the generated digits visually.

## Functions

1. **Generator and Discriminator Models**  
   - Define the architecture of the Generator and Discriminator networks.
   - Both models are trained together, with the Generator trying to produce realistic images and the Discriminator distinguishing real from fake images.

2. **Training the GAN**  
   - `train_gan`: Function to train the GAN using the Generator and Discriminator.
   - Loss functions for both the Generator and Discriminator are defined using Binary Cross Entropy.

3. **Image Generation and Plotting**  
   - `generate_and_plot_images`: Function to generate fake images using the trained Generator and display them in a grid.

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/SepehrAHJ/hoda-digit-gan.git
```

### 2. Install required libraries
```bash
pip install -r requirements.txt
```


## Requirements

- Python 3.x
- PyTorch
- Matplotlib
- NumPy

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
