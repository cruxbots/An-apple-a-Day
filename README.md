# An-apple-a-Day
My machine vision Assessment for counting apples in orchard farm from given images

Further details are given in the code itself check the code. Read below for Introduction and other information.

#Introduction
The main aim of this model is to count the total numbers of Apples in an particular image. But, this model does something extra, It's not only capable of counting apples but also capable to check that the apples you are gonna eat are in good condition if trained, but due to time restrictions i was not able to do this.
It does so by outputing the binary image of the input image in which there are two classes that are APPLEs and NOT Apples. One more distinctive feauture of this model is that, unlike traditional object detection models it does semantic segmentation that is it dosen't only outputs certain paramenters related to apples but the output of this model is EACH AND EVERY PIXEL IN THE IMAGE AS EITHER CLASS APPLE OR NOT APPLE.
This model has many advantages over other it can be also used for navigation if the camera is installed on a mobile robot. Many of the pros are already discussed above and many more are added in here. Since unet was originally made for biomedical imaging it requires significantly less amount of data to give an output, because it mostly depended upon the image augmentation.
One of the problem with this model is YELLOW LEAFES this recognise them as apples.
So, i think this model is going to be very good.

# How to use this and how you can use this 

It was my first machine vision code so please be easy on me and i would suggest that use this code as a refernce for developing your own code instead of using this as standalone project. (I may edit it further)
It is recomended that you use this code in google colab (as i did) and upload the dataset in appropriate file and also edit the code to especify the path of the dataset. 

You can download the dataset using this link https://conservancy.umn.edu/handle/11299/206575 there are 3 availaible files search for the one having binary iomages for this project.

I have manually sorted the images into training,testing and validation dataset (because at that time i was not sure how to do it using the code however you can do it. 

# Results

##Input image to the model
![Actual_image](https://user-images.githubusercontent.com/50763982/122678976-da488f80-d1e0-11eb-802b-4a4bea61e5c5.png)
Dosen't require much explaination i guess it is the input image given to the code that was never used for training.

##How it should look like in binary
![Ground_truth](https://user-images.githubusercontent.com/50763982/122679100-72467900-d1e1-11eb-920e-5a09811ff570.png)
This image is binary image (only black and white [you might already know that but i told u again hahahaha]) you can get them in the dataset (there are two files just browse them don't be lazy come on).

##Output image
![Result](https://user-images.githubusercontent.com/50763982/122679336-58f1fc80-d1e2-11eb-946c-ea6ee32841dd.png)
This is the resulting image from the output (doesn't it looks cool!!! yeah it is) 
You can just edit this code if you need localised information about the position of apples in the image.
This is binary image but i have made it to look this cool.
