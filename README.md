# Pneumonia Diagnosis

## Using Machine Learning to help healthcare
Using the x-rays provided, determine whether a given patient has pneumonia or not.
A Convolutional Neural Network was used and adjusted several times, in an attempt to increase accuracy.
The final accuracy was ~93 percent.

## EDA
At first, data exploration was neccessary to see what kind of images were provided. 
We were given a 'normal' folder, which contained healthy images. In addition to that, there were also 'Pneumonia' images that contained both bacterial and viral examples. 
Here are some example of each.
![Healthy_images.png](attachment:Healthy_images.png)
![V_images.png](attachment:V_images.png)
![Bac_images.png](attachment:Bac_images.png)

Of course, the purpose is to build a model that will do the work for us but, lets take a look to see if there's an visible difference to the naked eye.
![Comparison.png](attachment:Comparison.png)
It does seem like there are visual differences between a healthy set of lungs vs. one with pneumonia.

These are the parameters that ended up having the best accuracy.
![Model%20used.png](attachment:Model%20used.png)
