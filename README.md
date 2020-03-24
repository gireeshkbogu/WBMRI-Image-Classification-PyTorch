# WBMR-Image-Classification-PyTorch
Image classification using deep learning models in PyTorch.

## Description
This repository contains the implementation of CNN in PyTorch deep learning framework.

Image Classification is one of the basic and most important task of Deep Learning. In this repository, I am focussing on classifying WBMRI (Whole-Body Magnetic Resonance Images)  taken from different body parts and in axial, coronal and saggital angles.

## Download and Setup
Once you clone this repo, run the classify.py file to classify images in your own data/test_dataset.  

```
$pip install -r requirements.txt

$python classify.py
```

## Examples (Results)
##### Head and Neck (Axial) 
<div>
<img src="https://user-images.githubusercontent.com/3885659/77395146-d721e200-6d98-11ea-85b4-b8171be731bf.png" height="250" width="400">
<img src="https://user-images.githubusercontent.com/3885659/77460400-eafd3080-6df8-11ea-92ec-c555c5be9889.png" height="250" width="400">
</div>

##### Abdomen (Coronal)
<div>
<img src="https://user-images.githubusercontent.com/3885659/77395152-dbe69600-6d98-11ea-91ec-1bb38d93ea0f.png" height="250" width="400">
<img src="https://user-images.githubusercontent.com/3885659/77460381-e33d8c00-6df8-11ea-9f31-3c7d97d32444.png" height="250" width="400">
</div>
                                                                                                                                      
### Note:
The current model trained on a small number of images with a simple CNN but works well. No augmentation or transfer learning used. I will update the metrics, and different models, and with a large number of images in the future.  
