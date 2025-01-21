# MNIST Digit Classification with TensorFlow and python

This project implements a Convolutional Neural Network (CNN) for classifying handwritten digits using the MNIST dataset.

## Features
- CNN architecture with multiple convolutional and pooling layers
- Dense layers with ReLU activation
- Training metrics visualization
- Sample predictions display

## Requirements
- TensorFlow 2.x
- NumPy
- Matplotlib

## Model Architecture
- Input Layer: 28x28x1 (grayscale images)
- 3 Convolutional Layers with MaxPooling
- 2 Dense Hidden Layers (128 and 64 neurons)
- Output Layer: 10 classes (digits 0-9)

## Usage
```python
# Train the model
model.fit(x_train, y_train, epochs=10, validation_data=(x_test, y_test))

# Evaluate
test_loss, test_acc = model.evaluate(x_test, y_test)
```

## Results
- Training metrics visualization
- Sample predictions on test data
- Performance evaluation

## 📂 Participation Proof
Below are screenshots showing proof of participation in the project:

![Participation Proof 1](https://github.com/Kylapurity/Participation_Assignment/blob/main/Screenshot%202025-01-20%20195544.png)
![Participation Proof 2](https://github.com/Kylapurity/Participation_Assignment/blob/main/Screenshot%202025-01-20%20195559.png)
![Participation Proof 3](https://github.com/Kylapurity/Participation_Assignment/blob/main/Screenshot%202025-01-20%20195618.png)
![Participation Proof 4](https://github.com/Kylapurity/Participation_Assignment/blob/main/Screenshot%202025-01-20%20195633.png)
![Participation Proof 5](https://github.com/Kylapurity/Participation_Assignment/blob/main/Screenshot%202025-01-20%20195650.png)


## Team Members
- Bonyu Miracle: https://github.com/glenmiracle18
- Purity Kihiu: http://github.com/Kylapurity
- Peter Johnson: https://github.com/maxprodigy

## License
MIT License
