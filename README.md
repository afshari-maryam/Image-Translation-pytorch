# Image-Translation-pytorch
                           In the Name of Allah, the Beneficent, the Merciful
                           
This is the implementation of image translation using Unet Model in pytorch. </br>
You can see the code and result in ```Image _To_Image_Translation.ipynb ```.</br>
I wrote this code using jupyter notebook.</br>

## About the model architecture : 
The U-Net model is a popular architecture used for image translation tasks. It is particularly effective in tasks such as image segmentation, where the goal is to classify and differentiate different regions within an image. The U-Net architecture consists of an ```encoder-decoder structure``` with ```skip connections```.</br>

The ```encoder part``` of the network captures the high-level features of the input image through a series of convolutional and pooling layers.</br>
The ```decoder part``` of the network uses upsampling and transposed convolutions to generate a high-resolution output that matches the input image size.</br>
The skip connections, which connect corresponding layers from the encoder to the decoder, help preserve spatial information and aid in the accurate reconstruction of the output.</br>

The U-Net model has gained popularity due to its ability to handle both local and global features effectively. </br>

I used UNet in this implementation. </br>

## Results :
You can see the results of this implementation in below picture:</br>
The input images are in the first row and predicted images (outputs of model) are in the second row.</br>
![image](https://github.com/afshari-maryam/Image-Translation-pytorch/blob/main/Result.png)


