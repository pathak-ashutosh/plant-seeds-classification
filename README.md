# plant-seeds-classification
Can you differentiate a weed from a crop seedling?

The ability to do so effectively can mean better crop yields and better stewardship of the environment.

The Aarhus University Signal Processing group, in collaboration with University of Southern Denmark, has recently released a [dataset](https://vision.eng.au.dk/plant-seedlings-dataset/) containing images of approximately 960 unique plants belonging to 12 species at several growth stages.

This project is one of my very first projects on Machine Learning. What I've done here is, I took Kaggle's ["Plant seedlings classification" dataset](https://www.kaggle.com/c/plant-seedlings-classification/data) and used [mxnet](https://mxnet.apache.org/) framework on a [pre-trained resnet-50 model](http://data.mxnet.io/mxnet/models/imagenet-11k-place365-ch/) to get highest possible performance in least possible (dev) time.

## About the data
You are provided with a training set and a test set of images of plant seedlings at various stages of grown. Each image has a filename that is its unique id. The dataset comprises 12 plant species. The goal is to create a classifier capable of determining a plant's species from a photo. The list of species is as follows:

```
Black-grass
Charlock
Cleavers
Common Chickweed
Common wheat
Fat Hen
Loose Silky-bent
Maize
Scentless Mayweed
Shepherds Purse
Small-flowered Cranesbill
Sugar beet
```

## Setting-up
### What you need:
* A PC\notebook having a good GPU (cloud GPUs will also do)
* 
