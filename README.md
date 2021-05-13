# NeuralNetworkInExcel
Training a neural network in excel

![Screenshot](https://user-images.githubusercontent.com/65823721/118019102-39132180-b376-11eb-93a8-1997ccf173d5.PNG)

- Inputs are as i1 and i2 whose values are .05 and .1 respectively
- Inital weights are taken as shown in the figure
- We start forward propagation and calculate all the network parameters
- Activation function taken in this network is sigmoid
- At the end we calculate the error comparing output of the network and actual output(t1 and t2 in the excel sheet) 
- Then we start backpropagation and update weights one by one from the last layer to the first(Chain rule helps us in doing so)
- Once all the weights are updated then once again the cycle of forward propagtion and backward propagation repeats as many times as the number of epochs is
- The rate at which updation of weights takes place is controlled by learning rate
- Refer excel sheet for detailed formula(I used 0.5 as my learning rate and ran the neural network for 50 epochs)
