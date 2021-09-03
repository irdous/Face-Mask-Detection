# Face-Mask-Detection
During pandemic COVID-19, WHO has made wearing masks compulsory to protect against this deadly virus. In this I will develop a machine learning project – Real-time Face Mask Detector with Python.
Today it has become mandatory for all the citizens to wear a face mask to protect themselves from COVID-19. This application can be helpful for all the shop owners, offices, banks or any public place because if anyone is not wearing a mask then he or she must not be allowed in that area. So, to take care of this problem we don’t need any guard or person who keeps a watch on people. We can integrate a camera which continuously clicks pictures of humans and detect from there faces whether they are wearing a face mask or not.
### Steps to Perform
Load images using Python or any other programming you are working on.
Convert images into array
And finally apply some algorithm on that array
Another good thing is that we have a library known as OpenCV which will help us to read the image and return array of color pixels.
when we read any image using OpenCV it returns object of numpy array by default and using img.shape we are checking the height and width of image and also it returns 3 which is the color channel of image. Now we can see the values of array are the color values actually.
### Face Detection Using OpenCV
So now we are going to see how to detect face from an image. Face detection algorithm was introduced by Viola and Jones in 2001. They divided this algorithm in four stages :

1.Haar Features Selection

2.Integral Images

3.AdaBoost

4.Cascading Classifier

We do not have to worry about these steps right now because we already have a XML file which is going to help us to detect faces from the image.
