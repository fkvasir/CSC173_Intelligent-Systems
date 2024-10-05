# A Visual and Interactive Guide to the Basic of Neural Networks

> The calculation starts from the input node at the left.
>
> The input value flows to the right. It gets multiplied by the weight and the result becomes our output.

![Simple Diagram](https://jalammar.github.io/images/simple_NN_1.png "simple-diagram")

> Diagrams like this show you the structure of the network and how it calculates a prediction. The calculation starts from the input node at the left. The input value flows to the right. It gets multiplied by the weight and the result becomes our output.

But before that, we needed to think about the weight we’ll be multiplying by.

Finding the weight is our “training” stage. So whenever you hear of someone “training” a neural network, it just means finding the weights we use to calculate the prediction.

![Predictive Model](https://jalammar.github.io/images/NNs_formula_no_bias.png "predictive-model")

> This is a form of prediction. This is a simple predictive model that takes an input, does a calculation, and gives an output (since the output can be of continuous values, the technical name for what we have would be a “regression model”)
