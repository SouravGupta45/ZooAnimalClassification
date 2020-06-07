# ZooAnimalClassification
This Dataset was found on Kaggle .
This dataset consists of 101 animals from a zoo.
There are 16 variables with various traits to describe the animals.
The 7 Class Types are: Mammal, Bird, Reptile, Fish, Amphibian, Bug and Invertebrate

The purpose for this dataset is to be able to predict the classification of the animals, based upon the variables.
It is the perfect dataset for those who are new to learning Machine Learning.
zoo.csv

Attribute Information: (name of attribute and type of value domain)

    animal_name: Unique for each instance
    hair Boolean
    feathers Boolean
    eggs Boolean
    milk Boolean
    airborne Boolean
    aquatic Boolean
    predator Boolean
    toothed Boolean
    backbone Boolean
    breathes Boolean
    venomous Boolean
    fins Boolean
    legs Numeric (set of values: {0,2,4,5,6,8})
    tail Boolean
    domestic Boolean
    catsize Boolean
    class_type Numeric (integer values in range [1,7])

class.csv

This csv describes the dataset

    Class_Number Numeric (integer values in range [1,7])
    NumberOfAnimalSpeciesIn_Class Numeric
    Class_Type character -- The actual word description of the class
    Animal_Names character -- The list of the animals that fall in the category of the class
