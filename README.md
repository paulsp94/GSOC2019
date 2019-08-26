# GSOC2019 TensorFlow js

This website will give you an overview about the work done by me during the Google Summer of Code 2019.

## Model conversion

During this sub-project I converted multiple keras models to TensorFlow js models and made them available on github.
Additionally, I wrote a blog post which explains the workflow of converting a python keras model into a TensorFlow js model.
https://dev.to/paulsp94/convert-keras-models-to-tfjs-2k3


First I converted the VGG19 model that was pretrained on the ImageNet dataset. 
This model was then used for the Neural Style Transfer.
https://github.com/paulsp94/tfjs_vgg19_imagenet

Then I converted the ResNet50 model as an example for 
https://github.com/paulsp94/tfjs_resnet_imagenet

## Model as a package

https://www.npmjs.com/package/resnet_imagenet

## Skin Cancer Prediction

For the skin cancer prediction, I started of with a kaggle notebook, where I changed the model to the MobileNetV2 model.
Then I trained the model on kaggle and exported it into an hdf5 file. 
This file I converted to a TensorFlow js model like in the first section.
https://github.com/paulsp94/mobilenetv2skincancer

https://www.npmjs.com/package/mobilenetv2skincancer

## Style Transfer

https://github.com/paulsp94/tfjs_style_transfer
