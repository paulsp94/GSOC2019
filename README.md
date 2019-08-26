# GSOC2019 TensorFlow js

This website will give you an overview of the work done by me during the Google Summer of Code 2019.

## Model conversion

During this sub-project, I converted multiple Keras models to TensorFlow js models and made them available on GitHub.
Additionally, I wrote a blog post which explains the workflow of converting a python Keras model into a TensorFlow js model.

https://dev.to/paulsp94/convert-keras-models-to-tfjs-2k3


First I converted the VGG19 model that was pre-trained on the ImageNet dataset. 
This model was then used for the Neural Style Transfer.

https://github.com/paulsp94/tfjs_vgg19_imagenet

Then I converted the ResNet50 model as an example for the blog post and also as a base for an npm package.

https://github.com/paulsp94/tfjs_resnet_imagenet

## Model as a package

After converting the model into Javascript, I wanted to make it as accessible as easy as possible.

https://www.npmjs.com/package/resnet_imagenet

## Skin Cancer Prediction

For the skin cancer prediction, I started with a Kaggle notebook, where I changed the model to the MobileNetV2 model.
Then I trained the model on Kaggle and exported it into an hdf5 file. 
This file I converted to a TensorFlow js model like in the first section.

https://github.com/paulsp94/mobilenetv2skincancer

https://www.npmjs.com/package/mobilenetv2skincancer

## Style Transfer

https://github.com/paulsp94/tfjs_style_transfer

![alt text](./assets/styleTransfer/500_39807.625_style1.png "block1_conv1")
Style extraced from the first convolutional layer in the first convolutional block.

![alt text](./assets/styleTransfer/500_58900656_style2.png "block2_conv1")
Style extraced from the first convolutional layer in the second convolutional block.

![alt text](./assets/styleTransfer/500_29894260_style3.png "block3_conv1")
Style extraced from the first convolutional layer in the third convolutional block.

![alt text](./assets/styleTransfer/500_2514929.5_style4.png "block4_conv1")
Style extraced from the first convolutional layer in the fourth convolutional block.

![alt text](./assets/styleTransfer/500_82911.734375_style5.png "block5_conv1")
Style extraced from the first convolutional layer in the fifth convolutional block.

