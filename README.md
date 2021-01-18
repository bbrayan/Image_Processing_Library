# Number_Recognition
the purpose of this app is to learn basic image editing techniques
like and features as listed bellow.

applying 3x3 filters, in the example bellow i am using an edge tedection filter
![](image/filter.png)

finding the number of black pixel's in each connected region, also returning those regions as seprate images
![](image/multi.png)

scaling and image to certain dimentions, this can be done to a single images or every connected region in an image as shown bellow 
![](image/scaling.png)

thinning an image
![](image/thin.png)         
  

this app also allows you to recognize numbers to a limited extent
it is done using euclidon distance and feature vectors. 
![](image/8.png)
the image is converted into a feature vectores and are then compared to a number of other feature vectores of numbers who's value we already know and which ever one has the smallest euclidian distance is then predicted to be the number found in the image. 


in order to start the app you have to run menu.py
from the option menu you will be able to choose an operation
that you would like to perform and then enter the address of the image file
you would like to use it on
