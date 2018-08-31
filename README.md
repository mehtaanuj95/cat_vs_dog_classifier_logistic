# cat_vs_dog_classifier_logistic
A basic logistic regression based classifier to classify cats and dogs

**data_creation_h5py.ipynb** creates a h5 file from the raw images that we have. It also resizes the images to 64bits each. This is important because as the image dimentions (pixels) inccreases, the size of  the h5file also increases.

**gistic_regression.ipynb** has a logistic regression model to classify whether the image is a cat or a dog.
The loss function used is ```cross entropy loss function```.
The activation function used is - sigmoid function.

```
Dataset-1 : ALready optimised dataset.
dataset-2 : Created using data_creation_h5py.ipynb script.
```

## Dataset 1 Statistics
![Dataset 1 statistics](https://github.com/mehtaanuj95/cat_vs_dog_classifier_logistic/blob/master/comparison_dataset_1.PNG)

## dataset 2 Statistics
![dataset 2 statistics](https://github.com/mehtaanuj95/cat_vs_dog_classifier_logistic/blob/master/comparison_dataset_2.PNG)


