# Stanford-Cars-Body-Data

The data consist of images of cars categorised according to their body type. 

I've created this data from the "train" subset of the actual data provided in Standford's Cars Dataset (http://ai.stanford.edu/~jkrause/cars/car_dataset.html). For this, I've used "class" info as given for each car image but only for "train" data. The "class" in actual data is car name, from which I've extracted body types such as hatchback, sedan, SUV etc. and made them as classes in this dataset.

For convenience, I've renamed the actual file_name with the "class" as mentioned in the actual dataset. The "standford_cars_type.csv" can provide you additional detail about the name and manufacturer along with the original name of the image as in the "train" subset of Stanford's Cars Dataset as mentioned above.

This data can be used for building:
- Car Body Type Classifier
- Car Brand Classifier (You have to recreate the data for "Car Brand Classifier" accordingly.

## NOTE:
The "Other" subfolder in the dataset consists of images of "SuperCab" which can be either used as an additional class or can be merged in the existing "Cab" class.
