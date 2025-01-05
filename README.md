In this project, we used a Jupyter Notebook to do all of your coding and written explanations. We preprocessed a dataset for handwritten digit recognition, built a neural network, then trained and tuned that neural network using your data.

Step 1

Loaded the dataset from torchvision.datasets
Used transforms or other PyTorch methods to convert the data to tensors, normalize, and flatten the data.
Created a DataLoader for your dataset

Step 2

Visualized the dataset using the provided function and either:
Your training data loader and inverting any normalization and flattening
A second DataLoader without any normalization or flattening
Explored the size and shape of the data to get a sense of what your inputs look like naturally and after transformation. 
Provided a brief justification of any necessary preprocessing steps or why no preprocessing is needed.

Step 3

Using PyTorch, built a neural network to predict the class of each given input image
Created an optimizer to update your network’s weights
Used the training DataLoader to train your neural network

Step 4

Evaluated your neural network’s accuracy on the test set.

Tuned your model hyperparameters and network architecture to improve your test set accuracy, achieving at least 90% accuracy on the test set.

Step 5

Used torch.save to save your trained model.


The model achived high accuracy of 98%, and using different optimizer or different hyper parameterers didn't give any improvement on training the model.
