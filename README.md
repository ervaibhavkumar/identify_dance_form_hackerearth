# identify Dance Form Hackerearth
This repository contains code related to hackerearth deep learning challenge - Identify Dance form 

This includes setting up appropriate augmnetaions that can be made and the DataGenerator class that yields the appropriate images for the given batch size.

## Dance Forms
1. Manipuri
2. Bharatanatyam
3. Odissi
4. Kathakali
5. Kathak
6. Sattriya
7. Kuchipudi
8. Mohiniyattam


## Augmentations available
- Rotation 
- Scaling up 
- Scaling down 
- Horizontal flip 

## Deep learning models used
| Model | Training Accuracy | Validation Accuracy |
| :---: | :---: | :---: |
| VGG19  | 13.9%  | 4.8% |
| ResNet50  | 92.7%  | 41.6% |
| InceptionV3  | 96.8%  | 65.2% |
| InceptionResNetV2  | 94.2%  | 47.4% |
| MobileNetV2  | 95.5%  | 13.9% |
| InceptionV3 with callback and L1  | 96.6%  | 50.1% |
| InceptionV3 with above and Normalization  | 98.2%  | 73.97% |
| DeXpression  | 98.7%  | 61.4% |