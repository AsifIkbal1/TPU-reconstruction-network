# TPU-reconstruction-network
TPU reconstruction network
The notebook results slower than the previous one since the number of epochs and the early stopping patience has been increased. The model could improve by tuning learning rate, and other NN hyperparameters. A possibility could also be increase the number of inferences on the test set by enabling dropout also in inference.

An interesting aspect I found is that even though I shuffle players inside the network the reconstruction loss keeps decreasing.

This month's TPS allowed me to understand how TPU is incredibly fast and how complex is setting up a tabular pipeline for working on TPU, bugs are often difficult to spot and hard to fix.

Hope this notebook helps someone learn something new.

I hope to learn from other kagglers at the end of this TPS seeing top solutions.
