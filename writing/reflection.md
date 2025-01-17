## Names: Mordred Boulais, Haylee Pierce

### Image

![Picture of Neural Network Simulation](nn_picture.jpg)

### Performance

Did the network's output make sense?
How could you adjust weights or activation functions to improve accuracy?
What did you notice about how small changes (e.g., weights) affect outcomes?

The network's output did make sense, as the values chosen would indicate that
the processed data was the desired outcome (an image of a U.S. stop sign).
Our activation functions were referenced off of examples of sigmoid functions,
as that is relatively simple.

Applying an alternate set of values (shape = 3, color = 1, text = 5) gives the
a similar final value (0.9999 truncated), however, which indicates that the
calculations do not fully serve their purpose, or that the weights/bias are
improper. 

### Ethics

What potential biases or ethical considerations could arise in your example scenario?

We chose our bias value based on the fact that we are primarily referencing U.S. stop
signs, as that was our primary bias consideration in the construction of our example.
Ethically speaking, our system is relatively contained and less likely to be liable for
larger ethical concerns, seeing as it would likely only be used as part of a larger system.

### Reflection

What was easy to understand about the neural network?
What challenges did you face?

The easiest part to understand was probably the general outline of the neural
network. The most challenging part might have been picking equations and values
within the nebulous construction. We suspect we may have missed a calculation
in our implementation; adding it, we get 0.982 for both still. Thus, it's likely
something in how we are using our weights, which we are struggling to understand
how to implement in our equations/neurons.
