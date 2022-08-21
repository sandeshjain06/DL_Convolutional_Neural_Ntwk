# Convolutional Neural Networks

    Convolutional Neural Networks (CNNs) have an input layer, an output layer, numerous hidden layers, and millions of parameters, 
    allowing them to learn complicated   objects and patterns. It uses convolution and pooling processes to sub-sample the given input 
    before applying an activation function, where all of them are hidden layers that are partially connected, with the completely 
    connected layer at the end resulting in the output layer. The output shape is similar to the size of the input image.


![image](https://user-images.githubusercontent.com/91243691/185791988-d8d56ac2-91db-42ae-b7f3-8136071f690f.png)


**Steps to Achieve CNN Algorithm**

    
# 1. Convolution Layer

    Convolution layer is the first layer to extract features from an input image. 
    
    Convolutional layers are made up of set of filters that are applied to input image.Also known as Kernels.
    
    Output of convolutional layer is feature map which is representation of input image with filters applied.
    
    
    
# 2. Activation Layer
    
    Rectified Linear unit(ReLU) transform functions only activates a node if the input is above a certain quantity. 
    While the data is below zero, the output is zero, but when the information rises above a threshold. 
    It has a linear relationship with the dependent variable.
    
    
# 3. Pooling 
    
    Reduce the spatial size of input , making it easier to process and require less memory.
    
    Reduce no of parameters and makes training faster.
    
    Types of Pooling 
    1.Max Pooling      -  Max value of pixel from portion of images.
    2.Average Pooling  -  Average of all values from portion of the images.
    
    
# 4. Flattening
    
    Converts the multidimensional array to single dimensions.


# 5. Full Connected Layer
  
    The fully connected layer is a layer in which the input from the other layers will be flattened into a vector and sent. 
    It will transform the output into the desired number of classes by the network.
    

# 6. Padding 

    Applying 0's at the edges.    


# 7. Stridding 

    Stride determines how many pixel shift
    
    When Stride = 1, filter moves 1 pixel at a time.
    When Stride = 2, filter moves 2 pixel at a time.










