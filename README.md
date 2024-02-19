## Steganography using DL
This repository contains the literature review for our project.

This repo contains:

- Steganography Using Deep Learning document.
- Research papers
  - A_New_High_Capacity_Image_Steganography_Method_Combined_With_Image_Elliptic_Curve_Cryptography_and_Deep_Neural_Network:
This paper proposes a new high-capacity image steganography method based on deep learning. The Discrete Cosine Transform(DCT) is used to transform the secret image, and then the transformed image is encrypted by Elliptic Curve Cryptography(ECC) to improve the anti-detection property of the obtained image. To improve steganographic capacity, the SegNet Deep Neural Network with a set of Hiding and Extraction networks enables steganography and extraction of full-size images

  - futureinternet-10-00054-v2: 
This paper combines recent deep convolutional neural network methods with image-into-image steganography. It successfully hides the same size images with a decoding rate of 98.2% or bpp (bits per pixel) of 23.57 by changing only 0.76% of the cover image on average

   - Image_Steganography_A_Review_of_the_Recent_Advances:
The main goal of this paper is to explore and discuss various deep learning methods available in image steganography field. Deep learning techniques used for image steganography can be broadly divided into three categories - traditional methods, Convolutional Neural Network-based and General Adversarial Network-based methods.

  - Hiding Images in Plain Sight: Deep Steganography:
Unlike many popular steganographic methods that encode the secret message within the least significant bits of the carrier image, our approach compresses and distributes the secret image’s representation across all of the available bits.

- Datasets
  - [Linaeus 5 Image Dataset](https://chaladze.com/l5/#:~:text=Overview&text=Images%20are%20256x256%20pixels%2C%20color,400%20test%20images%20per%20class):
    -  5 classes: berry, bird, dog, flower, other (negative set)
    - Images are 256x256 pixels, color (downsampled versions: 128X128, 64X64 and 32X32 pixels).
    - 1200 training images, and 400 test images per class.
    - Images were downloaded from pixabay.com.
