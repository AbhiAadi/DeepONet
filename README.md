# DeepONet
This is the repository contains the code for my summer Reseach intern of DeepONet model, which is used for learning the non-linear operators by using the the special achitecture based on Universal approximation Theorem.The code is only trained for Double integration as an operator. Model contains two input network one is branch network which takes the discretized form of different functions at different sensor points and the other one is trunk network that takes the input as a location at which we wnat to predict the values for double integral of that function.

## Installation
- Clone the repository(If using Google Colab)
- Otherwise: Install the requirements using --> 'pip intsall gstools'
                                            --> 'pip install tensorflow'

## Objectives:
1. For any kind of functions, It takes the the discretized values of function at different location to predict the double integration values of that function at given location in the trunk network.

## Advantages of using that model:
- This model is more efficient then a normal neural network and also this model is trained very well on very less number of epochs.
- This model generalizes well then a normal neural network

## Scopes of errors:
1. For a simple sin and cos functions their is issue of integration constant factor in the predicted and analytical solution.

## Results:
### You can find the ppt in which I compare the Models performance.(i.e between DeepOnet model and ANN Model):
- Comparison between DeepONet model with ANN model in which we combine both the trunk and branch netwrok in a single netwrok as a Input. [Click Here](https://drive.google.com/file/d/1sG05jQM1Je9zFNHDAtbKqMYjV7nW0aPJ/view?usp=sharing).
- Comparison between ANN model by taking only function values at discretized points and predicted values at the sensor points. [Click Here]( https://drive.google.com/file/d/1q9tvT4S0bfqkCbzXYBPlp2EheEaxwNH7/view?usp=sharing).
