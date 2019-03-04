# Dog breed detector

The dog breed detector will accept any user-supplied image as input. 
If a dog is detected in the image, it will provide an estimate of the dog's breed (133 diffrent breeds). 
If a human is detected, it will provide an estimate of the dog breed that is most resembling. 

The algorithm could be used as part of a mobile or web app.


Documentation
-------------

This is my first CNN from scratch for detecting a dog's breed.

Install
--------

* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  
Unzip the folder and place it in this project's home directory, at the location `/dogImages`. 

* Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  
Unzip the folder and place it in the home directory, at location `/lfw`.  



More Information
----------------

If u want to put in your own picture of a dog (or a human), save the picture under the folder "test".


After Test:
* Accuracy of my own network: 22% (only 10 epochs)
* Accuracy network with transfer learning (VGG16): 63% (only 17 epochs)

Python version: 3.7.2

Contributing
------------

This was a project of the Deep Learning Nanodegree Program @ Udacity.
Written by Lars Erbelding.

License
-------

It is free software.

