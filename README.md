Question:2
Convolution Operations with Different Parameters
This demonstrates convolution operations using NumPy and TensorFlow/Keras on a 5×5 input matrix with a 3×3 kernel, exploring different stride and padding configurations. The script performs convolutions with:

Stride = 1, Padding = 'VALID'
Stride = 1, Padding = 'SAME'
Stride = 2, Padding = 'VALID'
Stride = 2, Padding = 'SAME'
The resulting feature maps for each case are printed, showcasing the impact of stride and padding on the convolution output.


Question 3:
CNN Feature Extraction with Filters and Pooling
This  demonstrates feature extraction techniques in Convolutional Neural Networks (CNNs) using edge detection and pooling operations. It consists of two tasks:

Task 1: Edge Detection Using Convolution
Load a grayscale image.
Apply the Sobel filter to detect edges in both the x-direction and y-direction using OpenCV (cv2).
Display the original image along with the filtered images.
Task 2: Max Pooling and Average Pooling
Generate a random 4×4 matrix as an input image.
Apply 2×2 Max Pooling and 2×2 Average Pooling using TensorFlow/Keras.
Print the original matrix, max-pooled matrix, and average-pooled matrix to observe the effect of pooling operations.

Question 4:
Implementing AlexNet and ResNet-like Model
This focuses on implementing AlexNet and a ResNet-like model using TensorFlow/Keras to understand deep learning architectures.

Task 1: Implement AlexNet Architecture
Define a simplified AlexNet model with convolutional layers, max pooling, fully connected layers, dropout, and an output layer.
Print the model summary after defining it.
Task 2: Implement a Residual Block and ResNet-like Model
Implement a residual block with skip connections.
Build a ResNet-like model with an initial convolutional layer, two residual blocks, and fully connected layers.
Print the model summary to visualize the network structure.
