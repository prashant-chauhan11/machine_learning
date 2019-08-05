It consist of 60000 32*32 color images containing one of 10 object classes, with 6000 images per class.
The label classes in the dataset are:
->airplane
->automobile
->bird
->cat
->deer
->dog
->frog
->horse
->ship
->truck
I have used the CNN with 6 convolution layers in addition with normalization and regularization with the help of dropout layer.
Data augmentation is also used to achieve better accuracy.


I have stopped the training of the model after 7 epochs because it was taking very long on my system.
As we can see the Validation Accuracy of the model is increasing with each epoch so, for better accuracy we will have to train the model for more no. of epochs.
