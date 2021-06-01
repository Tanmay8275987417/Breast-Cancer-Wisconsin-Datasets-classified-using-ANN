# **Breast Cancer Wisconsin Datasets classified using ANN**

## **Information About Project**

### Data Information

Breast Cancer Wisconsin datasets has 569 observations or Rows and 33 atttibutes or Columns.

Attribute Information:

1) ID number
 
2) Diagnosis (M = malignant, B = benign)
 
3) 32

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

Missing attribute values: none

Class distribution: 357 benign, 212 malignant
![image](https://user-images.githubusercontent.com/45824743/120284948-69e1d900-c2da-11eb-88e0-5e2c400b40b4.png)

### Model Building

Here I have build Sequential model of Artificial Neural Network with 30 inputs valuse with 2 hidden layers and Output layer.

1st hidden layer consist of 16 Neuron and relu activation function;

2nd hidden layer consist of 16 Neuron and relu activation function and;

Output layer having 1 output followed by Sigmoid activation function.

After building the model used adam Optimizer to change the attributes of th neural Network such as weights and learning rate to resuced the Losses.

### Results

By Training my model on training data evaluate the model:
![image](https://user-images.githubusercontent.com/45824743/120286690-28522d80-c2dc-11eb-885f-9453d1dbaa12.png)

Predicting the resulte on test data shown by graphical representation in the form of confusion matrix
![image](https://user-images.githubusercontent.com/45824743/120287103-8e3eb500-c2dc-11eb-86dd-dca4b48fe989.png)



