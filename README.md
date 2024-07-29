# Grokking
Experiments With Grokking

An unofficial implementation of "**Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets**"

Currently, `Grokking.ipynb` only demonstrates a very fundamental example of Grokking. You can experiment around with the hyperparameters defined in `main()`. 
With the current hyperparameters, the training took around 14 minutes on an L4 GPU. 

Note that for smaller datasets, achieving generalization will take significantly longer. And it is crucial to maintain a small batch size, as larger batch sizes lead to overly stable training, thereby reducing the necessary noise that Grokking depends on.
