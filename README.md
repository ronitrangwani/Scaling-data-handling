# ML Codes -Scaling-Data-Handling


## What is Scaling Data?
 
Scaling is a step of Data Pre Processing that is applied to independent variables or features of data. It basically helps to normalize the data within a particular range. Sometimes, it also helps in speeding up the calculations in an algorithm.

### Why and Where to Apply Feature Scaling? 
The real-world dataset contains features that highly vary in magnitudes, units, and ranges. Normalization should be performed when the scale of a feature is irrelevant or misleading and not should Normalize when the scale is meaningful.

The algorithms which use Euclidean Distance measures are sensitive to Magnitudes. Here, feature scaling helps to weigh all the features equally.

Formally, if a feature in the dataset is big in scale compared to others, then in algorithms where Euclidean distance is measured, this big scaled feature becomes dominant and needs to be normalized. 

### Examples of Algorithms where Feature Scaling matters 
1. K-Means uses the Euclidean distance measure here feature scaling matters. 
2. K-Nearest-Neighbors also require feature scaling. 
3. Principal Component Analysis (PCA): Tries to get the feature with maximum variance; here too, feature scaling is required. 
4. Gradient Descent: Calculation speed increase as Theta calculation becomes faster after feature scaling.

## Documentation

[Documentation](https://numpy-ml.readthedocs.io/en/latest/index.html)


## Demo

Below are some screenshot to give you a glimps of the project.
For more download the python file and install jupyter and run your file.


## Screenshots

![5 1 1 scaling ron](https://user-images.githubusercontent.com/62294536/157093741-bed2c582-87b1-4d2d-9ddc-c786f8355dba.png)
![5 2 data processing](https://user-images.githubusercontent.com/62294536/157093750-0a854a58-dc19-487c-9520-2d9bf56696e8.png)
