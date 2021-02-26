# Feb26Response

## Convolve the two 3x3 matrices that were assigned to you with your 9x9 matrix and calculate the resulting two matrices

### Original Matrix 
<code>
       
       [[ 0,  0, -1,  0,  0,  2,  1,  0, -1],
       [-1,  0,  0, -2, -1,  0, -1, -1, -1],
       [ 0,  0,  1,  1, -2,  0, -1, -1, -1],
       [-1,  1,  1,  0,  0,  1,  1,  1,  0],
       [-1,  1,  1, -2,  2,  2,  0,  1,  1],
       [-1,  0, -1, -1, -2,  1,  1,  1, -1],
       [ 0,  0,  1, -1, -1, -2,  1, -1,  0],
       [ 0, -1, -1,  2,  1, -1, -1,  0, -1],
       [ 1, -1,  1, -2,  2,  1, -1,  0, -1]] 9x9 matrix

### Kernel1
<code>
       
       [[0, 0, 0],
       [0, 1, 1],
       [1, 0, 1]]
       3x3 matrix


### Kernel1 convolved over matrix output
<code>
       
       [[ 1, -1, -4,  0, -4, -3, -4],
       [ 1,  3,  0, -1,  0,  0, -1],
       [ 2,  0,  3,  1,  4,  5,  2],
       [ 0, -2, -3,  4,  1,  3,  2],
       [ 0, -3, -3, -4,  2, -1,  1],
       [ 0,  1, -2, -2, -1, -1, -3],
       [ 0, -2,  6, -1, -1,  0, -3]]
       7x7 matrix

### Kernel2
<code>
       
       [[0, 0, 1],
       [1, 1, 1],
       [1, 0, 0]]
       3x3 matrix


### Kernel2 convolved over matrix output
<code>
       
       [[-2, -2, -2,  0, -3, -2, -5],
       [ 0,  1,  0, -1, -4, -2, -3],
       [ 1,  4,  0, -1,  3,  4,  1],
       [ 1,  0,  0,  2,  3,  5,  3],
       [-1, -4, -1, -1, -1,  2,  3],
       [ 0, -2, -4, -1,  0, -2, -2],
       [ 0, -2,  2, -2,  2, -2, -3]]
       7x7 matrix


## What is the purpose of using a 3x3 filter to convolve across a 2D image matrix?
We use filters so that we can extract/preserve/highlight the features of the image that we deem important.
Using filters on an image helps reduce processing times as well since the computer is only processing the features that are important.


## Why would we include more than one filter? How many filters did you assign as part of your architecture when training a model to learn images of numbers from the mnist dataset?
You would include more than one filter to highlight multiple features of an image. 
Or maybe use one filter in conjunction with another with the idea that the first filter would highlight specific features that would then make it easier to highlight other features in the image.
If I remember correctly we


## MSE: From your 400+ observations of homes for sale, calculate the MSE for the following.
The 10 biggest over-predictions
The 10 biggest under-predictions
The 10 most accurate results (use absolute value)


## In which percentile do the 10 most accurate predictions reside? Did your model trend towards over or under predicting home values?
## Which feature appears to be the most significant predictor in the above cases?
## Stretch goal: calculate the MAE and compare with your MSE results
