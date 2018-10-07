# Hand Written Number Classification using Hardware Neural Networks
Implemented a Single Layer of Neural Network in **Verilog** which takes in a 28x28 pixel gray scale image of a hand written number, recognizes it and outputs what number it is.



* There are a total of 10 Neurons in the layer representing the number 0 to 9. Each neuron take inputs from all pixels and outputs the probability that the input is that particular number.

* Our design uses a combination of pipelining (to reduce area) and parallelism (to increase speed) to optimize the EAP.

* The design was synthesised in 32nm technology. High-Vt was used to reduce the leakage power.
