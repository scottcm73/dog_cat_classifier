# Dog/Cat Classifier

This fastai application will use convolution neural networks to classifier images as either dog or cat.

## Getting Started
The data is derived from a tarred file with the images and labels. In this data set the labels are based on the file names. The project gets the data from the Oxford-IIIT Pet Dataset by O. M. Parkhi et al., 2012 which features 12 cat breeds and 25 dogs breeds. The model will learn to differentiate between these 37 distinct categories.

The untar_data function takes a URL as an argument. It will download and extract the data.


### Prerequisites


For the learning step the of the neural networks you will need to run linux on a system with an NVIDIA GPU (CUDA capable GPU). There are ways around the GPU requirement, put they are extremely slow in comparison. 

I specifically used Linux Ubuntu on a dual-boot PC that I purchased and set up myself. 

Once ubuntu is installed, you must install Fastai, vscode, Kindle and sublime. 

Kindle installation for ubuntu is a bit tricky, because the at the time of installation the latest version did not work with ubuntu, and a previous version was required. 

Kindle is needed to follow along with the Fastai book and course.

Anaconda is also required to get the necessary dependencies

### Installing
Details and instructions for the Anaconda installation on linux are at: 
https://docs.anaconda.com/anaconda/install/linux/

An explanation of the Fastai installation can be found at: https://github.com/fastai/fastai1/blob/master/README.md#installation

Sublime installation instructions are at:

https://linuxize.com/post/how-to-install-sublime-text-3-on-ubuntu-18-04/






## Running the tests

Testing will be performed locally before deployment.


## Deployment

I will attempt to deploy on a Bluehost VPS running Centos.

## Built With

*  fastai.vision.all
*  nbdev.showdoc
*  matplotlib
 

## Versioning

Github was used for versioning. For the versions available, see https://github.com/scottcm73/dog_cat_classifier


## Author

* The original authors are Jeremy Howard and Sylvain Gugger. 


However, I will attempt to deploy the saved model on a system without a gpu once the learning is accomplished. 
* **Scott McMahan** -- will be the author of the deployed version.



## License



## Acknowledgment

The majority of the code for this comes from the book, Deep Learning for Coders with fastai and Pytorch. The 

## Reference

Gugger, S., Howard, J. (2020). Deep Learning for Coders with fastai and Pytorch: AI Applications Without a PhD. O'Reilly Media Inc. 





