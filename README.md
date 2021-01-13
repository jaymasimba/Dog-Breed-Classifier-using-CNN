[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Overview

In the initial project, we develop an algorithm that can can be used as part of a mobile or web app for dog breed classification. The project takes any user-supplied image as input and supplies gives a breed classification if a dog is detected otherwise it gives the closest breed resemblance if a human is detected.

The initial part of the project is to create a deepl learning architecture that can classify different breeds of dogs with an accuracy of over 10%. The created architecture(partly inspired by the squeezenet architecture) has on accuracy of 17% based on 23 epochs of training with room for improvement with further training.

The second part was to improve the model further by using a pretrained model. For this part, we selected the pre-trained resnet50 model and trained it over the images. The accuracy of the new model was 80% This project is part of the udacity Deep learning nano degree program. 

![Sample Output][image1]

