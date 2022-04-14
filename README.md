# EfficientNets

Efficient Net is an advanced neural network architecture and scaling method that uniformly scales all dimensions of depth/width/resolution using a compound coefficient. The EfficientNet models achieve both higher accuracy and better efficiency over existing CNNs, reducing parameter size and FLOPS by an order of magnitude. It is a lightweight model (can be used in android apps) and gives more accuracy even with less parameters.

In EfficientNet, we scale all 3 components i.e.
                                                  1. Depth
                                                  2. Width
                                                  3. Resolution
                                                  
## Depth Scaling

Depth Scaling means increasing the depth i.e. the number of layers in a network to obtain better accuracy.


                                                  
## Width Scaling 

It refers to altering the width of the input image. Wider the image more the number of feature maps/channels possible hence more the information available to process on. This in turn leads to better conclusions and predictions.


## Resolution Scaling

Resolution Scaling refers to altering the resolution of an image. The more the DPI (Dots per Inch) of an image, the better the resolution. In simpler terms, better resolution refers to an increase in the number of pixels in an image.


Blog Link - https://blog.devgenius.io/efficient-nets-rethinking-model-scaling-f342ee7bb021
