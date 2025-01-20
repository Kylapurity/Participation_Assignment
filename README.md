# MNIST Digit Classification with TensorFlow

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
model.fit(x_train, y_train, epochs=5, validation_data=(x_test, y_test))

# Evaluate
test_loss, test_acc = model.evaluate(x_test, y_test)
```

## Results
- Training metrics visualization
- Sample predictions on test data
- Performance evaluation

## Team Members
- Bonyu Miracle: 
- Purity Kihiu: 
- Peter Johnson: 

## License
MIT License
