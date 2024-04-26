# ANN-with-Arduino
 The neural network in this example is a feed-forward backpropagation network as this is one of the most commonly used, the network concept will be described briefly in the background section.
 An artificial neural network is a mathematical computing model which is designed to mimic the way in which the brain reacts to sensory inputs. The brain is made up of millions of neurons which are connected to each other in huge networks. Each neuron is capable of being stimulated, much like a switch being turned on or off, and the state of the neuron turns surrounding neurons on or off as well depending on the level of activation of the neuron and the strength of the connection between the neurons. A neuron with a strong connection will have a greater level of stimulation than one with a weaker connection.
\n Understanding The Code:
 Set up the arrays and assign random weights.
 Start a loop which runs through each item of training data.
 Randomise the order in which the training data is run through each iteration to ensure that convergence on local minimums does not occur.
 Feed the data through the network calculating the activation of the hidden layer’s nodes, output layer’s nodes and the errors.
 Back propagate the errors to the hidden layer.
 Update the associated weights.
 Compare the error to the threshold and decide whether to run another cycle or if the training is complete.
 Send a sample of the training data to the Serial monitor every thousand cycles.
