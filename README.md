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


