# Predicting the Markets Next Move-Building a Stock Price Prediction Model with LSTMs
### Detailed Explanation of evevry step performed is explained in python code itself 
### Some FAQ related to project
### Q1 Why there is conversion of data into supervised learning?
### Ans 1 Learning Dependencies: LSTMs are designed to capture long-term dependencies within sequential data. Supervised learning provides labeled data, where each sequence has a corresponding desired output. This allows the LSTM to learn the relationship between the elements in the sequence and the target output.Error Correction and Backpropagation: Supervised learning allows for error correction during training. The LSTM makes a prediction based on the sequence, and the model compares it to the actual labeled output. If there's a mismatch, the error is backpropagated through the network. This helps the LSTM adjust its internal parameters and learn from its mistakes to improve future predictions.Without labeled data for comparison, an unsupervised LSTM wouldn't have a clear target or a way to measure its success
### Q2 What is Training Validation and Testing period?
### Ans 2 Training-Model learns the mapping between inputs and outputs
###       Validation-Fine-tune hyperparameters to prevent overfitting and improve model performance
###       Testing-Evaluate the model's generalizability on unseen data
### Q3 What is activation function and which activation function is used in this porject 
### Ans 3 In deep learning, an activation function is a critical component within artificial neurons. It introduces non-linearity into the network, allowing it to learn and model complex relationships between data
### The Need for Non-linearity:If a deep learning network only used linear functions (without activation functions), it would essentially be a stack of linear regression models. Such a network would be limited to modeling only linear relationships between inputs and outputs.
### In this project relu as activation function is used ReLU (Rectified Linear Unit): Outputs the input directly if it's positive, otherwise outputs zero. Popular choice due to its computational efficiency and ability to avoid the vanishing gradient problem.
### Q4 What  is epoch?
### Ans 4 an epoch refers to one complete pass through the entire training dataset. It's a way of measuring the progress of the training process.
### Q5 What do you mean by  Learning rate and Loss function?
### Ans 5 Learning Rate -It controls how much the model adjusts its internal parameters (weights and biases) based on its mistakes.
### Higher learning rate: Larger steps, faster learning, but can be unstable and miss the optimal solution.
### Lower learning rate: Smaller steps, slower learning, but more stable and likely to converge on a good solution
### Loss function-It quantifies the difference between the model's predictions and the actual desired outputs (labels) for a given data point.
### Q6 Explain the optimiser and loss function used in this project?
### Ans6 Loss Function(mse)-MSE loss calculates the average squared difference between predictions and targets, guiding the model towards better accuracy.
### Optimiser (Adam)-Adam, which stands for Adaptive Moment Estimation, is an optimizer used in deep learning to efficiently update the internal parameters (weights and biases) of a model during training
### Q7 What do you means if learning rate=0.001 and epoch=100?
### Ans 7 An epoch represents one complete pass through the entire training dataset.So, epoch = 100 means the model will be exposed to the entire training data 100 times during training.
### With a learning rate of 0.001, the model will make small adjustments to its parameters in each iteration.The learning process will be slow with improved stability


