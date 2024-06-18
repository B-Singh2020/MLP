I used this project to dive deeper into the world of Multilayer Perceptrons (MLPs) and neural networks in general. I used PyTorch to build a model that can classify handwritten digits from the MNIST dataset. Essentially, the model is learning to recognize individual numbers (0-9) from grayscale images.


![image](https://github.com/B-Singh2020/MLP/assets/48160814/f0a49a40-b296-4301-bc8f-e6f57e3a09ae)

The project focuses on clear and well-structured code, breaking down the process into steps:

First, I prepped the data by normalizing it and splitting it into training, validation, and test sets. This helps the model train effectively and avoid biases.
Then, I defined the MLP architecture itself. It has multiple hidden layers, each applying an activation function to transform the data.
To train the model, I used the Adam optimizer and the cross-entropy loss function. There's also a loop that calculates the model's accuracy on each batch of data.
A separate loop evaluates the model's performance on the validation set during training. This helps me track how well the model is generalizing to unseen data.
Finally, I implemented a technique to save the model that performs best based on the validation loss.
Overall, this project has been a great way to learn about the fundamentals of building and training image classification models with PyTorch. 


Some possible extensions for this project include:
- Test the model on a completely different dataset to see how well it generalizes
- Try another model type, like CNN
- Add more layers to the current MLP model (deeper network)
- Add more neurons per layer into the MLP (wider network)





