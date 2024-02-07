# AlgoSurge_ProSpace
This repo contains the code for the assignment of the surgical computer vision project offered by ProSpace under the file image_segmentation.ipynb.

In this code, I have defined a simple CNN model and trained it over generated synthetic dataset for image segmentation. The ouput displays the generated and the masked images, where shapes get segmented out.

I have also utilised transfer learning by importing the pre-trained weights of maskrcnn_resnet50 model using the torchvision library. Then I have shown each mask which successfully demonstrated instance segmentation.
Note: For this, the image over which segmentation needs to be performed, is imported by specifying the URL of the image taken from the Internet.
