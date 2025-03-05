# Conditional GANs (cGAN) for Fashion MNIST

## Objective
This project focuses on implementing Conditional Generative Adversarial Networks (cGAN) in PyTorch to generate  fashion images similar to the Fashion MNIST dataset. Through this project, we can generate specific types of clothes from the dataset such as shirts, pants, shoes, and many more by conditioning on class labels.

## Dataset
Fashion MNIST (28x28 grayscale images, 10 classes):
Downloaded automatically via Torchvision

### Exploratory Data Analysis
![Training images](./images/training_images.png)

#### Data Distribution
![Bar plot of the output data distribution](./images/output_class_distribution.png)

## CGAN Generated Images
### GIF of CGAN Generated Images (During Training)
![GIF of the generated images](./images/generated_images.gif)

### Generated Image: Across All Labels
![Generated Images](./images/Image_Epoch_100.png)

### Generated Images of T-shirts/ Tops
![](./images/cgan_generated_tshirts.png)

### Generated Images of Trousers
![](./images/cgan_generated_trousers.png)

### Generated Images of Pullovers
![](./images/cgan_generated_pullovers.png)

### Generated Images of Dresses
![](./images/cgan_generated_dresses.png)

### Generated Images of Coats
![](./images/cgan_generated_coats.png)

### Generated Images of Sandals
![](./images/cgan_generated_sandals.png)

### Generated Images of Shirts
![](./images/cgan_generated_shirts.png)

### Generated Images of Sneakers
![](./images/cgan_generated_sneakers.png)

### Generated Images of Bags
![](./images/cgan_generated_bags.png)

### Generated Images of Ankle Boots
![](./images/cgan_generated_ankle_boots.png)

## Conclusion
This project shows how we can solve one major issue with traditional GANs- the controllability of the output. Through Conditional GANs, we have successfully trained the discriminator and the generators to take ‘y’ label as an input which is used to help generate specific types of image outputs.

## Installation
To run this project, I used Python 3.10.10 and PyTorch. Install dependencies using:
```bash
pip install -r requirements.txt
```

## How to Run
This project can be run in a Jupyter Notebook.
Steps:
1. Clone the repository and navigate to the project directory:
    ```
    git clone https://github.com/rkaushick-neu/cgans/
    cd cgans
    ```
2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter notebook:
    ```bash
    jupyter notebook Rish_CGANs.ipynb
    ```
4. Run all the cells to train the model and generate class specific fashion images.

## Author
Rishabh Kaushick

For any questions, feel free to reach out via GitHub Issues.