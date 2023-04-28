# EVA-8_Phase-1_Assignment-13

## Introduction

## Part-1 : UNET implementation with different varient
### Implementation-1: 
Notebook `EVA-8_Phase-1_Assignment-13\Part1-Unet-implementation\MaxPool_TransConv_Criterion.ipynb` contains the first implementation of UNET.
<br> 
Below ar the creteria for the frist implementation:
 - Max-Pooling for reduction
 - Transpose-Convolution for upscaling
 - Binary-Cross-Entropy for loss calculation
<br>
Below are the results in the form of generated output mask and loss-accuracy plot for training.

![alt-text-1](Part1-Unet-implementation/util/out1.png "output1") ![alt-text-2](Part1-Unet-implementation/util/graph1.png "graph1")


### Implementation-2: 
Notebook `EVA-8_Phase-1_Assignment-13\Part1-Unet-implementation\MaxPool_TransConv_Dice.ipynb` contains the second implementation of UNET.
<br> 
Below ar the creteria for the second implementation:
- Max-Pooling for reduction
- Transpose-Convolution for upscaling
- Dice loss for loss calculation

<br>
Below are the results in the form of generated output mask and loss-accuracy plot for training.

![alt-text-1](Part1-Unet-implementation/util/out2.png "output1") ![alt-text-2](Part1-Unet-implementation/util/graph2.png "graph1")

### Implementation-3: 
Notebook `EVA-8_Phase-1_Assignment-13\Part1-Unet-implementation\StrideConv_TransConv_Criterion.ipynb` contains the third implementation of UNET.
<br> 
Below ar the creteria for the third implementation:
 - Strided-Convolution for reduction
 - Transpose-Convolution for upscaling 
 - Binary-Cross-Entropy for loss calculation

<br>
Below are the results in the form of generated output mask and loss-accuracy plot for training.

![alt-text-1](Part1-Unet-implementation/util/out3.png "output1") ![alt-text-2](Part1-Unet-implementation/util/graph3.png "graph1")

### Implementation-4: 
Notebook `EVA-8_Phase-1_Assignment-13\Part1-Unet-implementation\StrideConv_TransConv_Dice.ipynb` contains the fourth implementation of UNET.
<br> 
Below ar the creteria for the fourth implementation:
 - Strided-Convolution for reduction
 - Transpose-Convolution for upscaling 
 - Dice loss for loss calculation

<br>
Below are the results in the form of generated output mask and loss-accuracy plot for training.

![alt-text-1](Part1-Unet-implementation/util/out4.png "output1") ![alt-text-2](Part1-Unet-implementation/util/graph4.png "graph1")

### Implementation-5: 
Notebook `EVA-8_Phase-1_Assignment-13\Part1-Unet-implementation\StrideConv_Upsample_Dice.ipynb` contains the fifth implementation of UNET.
<br> 
Below ar the creteria for the fifth implementation:
 - Strided-Convolution for reduction
 - `nn.UpSample` for upscaling 
 - Dice loss for loss calculation

<br>
Below are the results in the form of generated output mask and loss-accuracy plot for training.

![alt-text-1](Part1-Unet-implementation/util/out5.png "output1") ![alt-text-2](Part1-Unet-implementation/util/graph5.png "graph1")

### Implementation-6:
Notebook `EVA-8_Phase-1_Assignment-13\Part1-Unet-implementation\StrideConv_Upsample_Criterion-Dice.ipynb` contains the sixth implementation of UNET.
<br> 
Below ar the creteria for the sixth implementation:
 - Strided-Convolution for reduction
 - `nn.UpSample` for upscaling 
 - (Dice loss + Criterion loss) for loss calculation

<br>
Below are the results in the form of generated output mask and loss-accuracy plot for training.

![alt-text-1](Part1-Unet-implementation/util/out6.png "output1") ![alt-text-2](Part1-Unet-implementation/util/graph6.png "graph1")

## Part-2 : VAE implementation with MNIST and CIFAR
### Mnist implementation
##### images with labels into the pipeline
![alt-text-1](Part2-VAE-implementation/util/mnist_org.png "output1") 
##### images without labels
![alt-text-2](Part2-VAE-implementation/util/mnist_rand.png "graph1")

### CIFAR implementation
##### images with labels into the pipeline
![alt-text-1](Part2-VAE-implementation/util/cifar_org.png "output1") 
##### images without labels in the inferencing pipeline
![alt-text-2](Part2-VAE-implementation/util/cifar_rand.png "graph1")