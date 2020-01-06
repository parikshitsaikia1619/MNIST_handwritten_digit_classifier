# MNIST_handwritten_digit_classifier
 A nn model using pytorch which classifies between different handwritten digits (0-9).
 
 this is a classic problem of classifing hand written digits.
 the dataset is collected from MNIST .
 
 *note: there are many uncessary codes in this project for debugging purposes and also to get familiar with pytorch.
 Because I'm new to this thing*
 
 overview of the approach:
 1. download the dataset.
 2. preprocessing , transforming into tensor before loading the dataset in our trainloader (of bacthsize 64).
 3. image.tensor.size() =(64 * 28 * 28)
 4. create the nn model i/p : 784 nodes , hidden layer: 1,2 , o/p node: 10
 5. train the model.
 6. activation functions relu for hidden , softmax for o/p
 7. error function : natural log loss
 8. optimizer :stocastic gradient descent
