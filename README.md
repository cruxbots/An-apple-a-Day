# An-apple-a-Day
My machine vision Assessment for counting apples in orchard farm from given images

#Introduction
The main aim of this model is to count the total numbers of Apples in an particular image. But, this model does something extra, It's not only capable of counting apples but also capable to check that the apples you are gonna eat are in good condition if trained, but due to time restrictions i was not able to do this.
It does so by outputing the binary image of the input image in which there are two classes that are APPLEs and NOT Apples. One more distinctive feauture of this model is that, unlike traditional object detection models it does semantic segmentation that is it dosen't only outputs certain paramenters related to apples but the output of this model is EACH AND EVERY PIXEL IN THE IMAGE AS EITHER CLASS APPLE OR NOT APPLE.
This model has many advantages over other it can be also used for navigation if the camera is installed on a mobile robot. Many of the pros are already discussed above and many more are added in here. Since unet was originally made for biomedical imaging it requires significantly less amount of data to give an output, because it mostly depended upon the image augmentation.
One of the problem with this model is YELLOW LEAFES this recognise them as apples.
So, i think this model is going to be very good.

# How to use this and how you can use this 

It was my first machine vision code so please be easy on me and i would suggest that use this code as a refernce for developing your own code instead of using this as standalone project. (I may edit it further)
It is recomended that you use this code in google colab (as i did) and upload the dataset in appropriate file and also edit the code to especify the path of the dataset. 

You can download the dataset using this link https://conservancy.umn.edu/handle/11299/206575 

I have manually sorted the images into training,testing and validation dataset (because at that time i was not sure how to do it using the code however you can do it. 
