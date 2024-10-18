
# Fashion GAN

This Generative Adversial Model is trained on FashionMNIST. The goal is to generate new Fashion Images based on the dataset




## Techstack
Python, Pytorch, TorchVision, Matplotlib

## Architecture

### Generator Block
- Linear
- BatchNorm1D
- ReLu

### Discriminator Block
- Linear
- LeakyReLU

### Generator Model Layers
- Generator Block
- Generator Block
- Generator Block
- Generator Block
- Linear
- Sigmoid

### Discriminator Model Layers
- Discriminator Block
- Discriminator Block
- Discriminator Block
- Linear

## Results

This is the after step 1000:

![image](https://github.com/user-attachments/assets/6da58d77-7e91-4b71-9800-77fd614b29b8)


This is after training the model for 400 epochs:

![image](https://github.com/user-attachments/assets/95f072a7-d86c-4812-970b-1b2451adfa53)


##Outputs
The model weights for Generator and Discriminator are in gen.pth and disc.pth
