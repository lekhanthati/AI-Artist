# GenAI-Artist

## Objective:

Devlop an advaced algorithm that is able to generate human faces without any help or human intervention. The primary goal is to leverage the Generative AI techniques and Tensorflow to develop a effictive algorithm that can output accurate images which are hard to distinguish.

## Output 

Here are the outputs form the combined model at different epochs.

![Screenshot 2024-04-12 194444](https://github.com/lekhanthati/AI-Artist/assets/153913544/f5334f08-73a6-4693-8ffe-7c76a6b0a9ec)


## Working with Image data 

When it comes to image data, Machine Learning Algorithms can directly interpret image data as our brains do. But this is possible by converting images into numerical representation. There are different Libraries and Frameworks helps to deal with image preprocessing like OpenCV.
Today we are checking out application of Generative AI with image data. There are to parts for the algorithm.
1)	Generator
2)	Discriminator

And the netowork is known as Generative Adverseral Networks (GAN's)


## Generator 


1)	The generator takes random noise vector as input.
2)	And passed through multiple hidden layers. 
3)	And the output is generated as per the training process like Image, text or number.


## Discriminator 

1)	Takes the real input directly or form the Generator.
2)	Passes through multiple hidden layers. 
3)	Classifies the input as real or fake (Generated by the generator).


## Steps 

1)	Let’s assume there are 100 images to be trained and the images have been pre-processed.
2)	Generator is trained on the real images. 
3)	Discriminator will not be working during the training of Generator and Vise versa.
4)	Out of the 100 images, 50 real images and 50 images generated by the Generator are classified with appropriate output and passed through the algorithms randomly during the training of Discriminator.
5)	 The algorithm is trained till the desired value of metric such that the Generator is able to generate real like images till the point the Discriminator is unable to identify.


## Thank you
