### Karl Vincent M. Espiritu  
### 2015-05691

### CoE 197Z - HW 1

**Multilayer Perceptron (MLP)**  
- [3 Layered Multilayer Perceptron](https://github.com/espiritukarl/EEEworks/blob/master/3layerMLP.ipynb)  
- MLP is a type of __feedforward artificial neural network__ that is characterized by its layers being fully connected to one another. An MLP would usually consist of an input layer, hidden layer(s), and an output layer. This model is made up of multiple neurons and are trained by adjusting its parameters, weights and biases. An MLP has 2 directions, and it is only forward and backward. Forward to send the inputs into hidden layers and against the ground truth to create an output, backward using backpropagation to train the model into a more accurate state.


**Convolutional Neural Network (CNN)**  
- [3 Layered Convolutional Neural Network](https://github.com/espiritukarl/EEEworks/blob/master/3layerCNN.ipynb)
- CNN is a classification of a deep neural network that are regularized versions of MLP. CNNs function by having it apply various relevant filters to the input (usually an image) and then scans its input with a kernel size, which has a smaller size than its input image, and shifts it until it coveres the whole image. From this, a __convolved feature__ is created and is actually the first layer to a CNN - the Kernel/Filter. The objective of doing this for its hidden layers, is to extract high level features from the image to form a pattern for its data. With the patterns, it may then find the classification of the image.


**CNN vs MLP**
- For the homework, it is evident that the CNN outperformed the MLP in terms of accuracy. The CNN notched a 76% accuracy while the MLP tallied just under 51%. 
- This is due to the dataset CIFAR10 being comprised of images. These images consists a 3 dimensional array with its RGB structure. The input data already benefits CNN as its input layer requires a 3D Tensor, on the other hand an MLP requires a 2D Tensor. 
- Another reason for the higher accuracy of CNN in the CIFAR10 dataset is how it classifies the input to the output. Remember that CNN looks for patterns, which images have while MLP merely looks at the pixels, which may confuse it given that its a 3D tensor.
- Finally, CNN is a more specific MLP but it specializes in image data (as shown by my reasons earlier). That is why it has a higher accuracy.
