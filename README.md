# OCR with Naive Bayes and Perceptron Algorithms

This repository contains a notebook in which I applied the Naive Bayes (NB) and Perceptron algorithms to classify images of handwritten digits into their corresponding numerical labels. The notebook is divided into two main sections, one for each algorithm, and further divided into subsections addressing different aspects of the model.

## Datasets

The datasets consist of images of handwritten digits and their corresponding labels. Each image is represented as a text file where each digit is drawn using symbols like "+", "-", etc. The labels are provided in separate text files. The datasets are divided into training, testing, and validation sets.

## Naive Bayes

### Section A - Hyperparameter Tuning
In this section, I explored the effect of varying the hyperparameters of the Naive Bayes model on its performance. I experimented with different values of the hyperparameters and evaluated the model's performance to determine the optimal set of hyperparameters.

### Section B - Testing with Tuned 'K'
In this section, I used the optimal hyperparameters identified in the previous section to test the performance of the Naive Bayes model on the test dataset.

### Section C - Testing on Training Labels
In this section, I tested the performance of the Naive Bayes model on the training labels and discussed the differences in accuracy between the training and test datasets. I also explored the reasons behind these differences.

## Perceptron

### Perceptron Class and Functions
In this section, I defined the Perceptron class and the functions necessary for its implementation.

### Perceptron with EPOCHS = 3
In this section, I trained and tested the Perceptron algorithm with a fixed number of epochs (EPOCHS = 3) and evaluated its performance.

### Training Data
In this section, I trained the Perceptron algorithm on the training dataset and evaluated its performance.

### Testing Data
In this section, I tested the performance of the Perceptron algorithm on the test dataset.

### Perceptron with EPOCHS in [1,5]
In this section, I experimented with different numbers of epochs (ranging from 1 to 5) and evaluated the performance of the Perceptron algorithm for each value of EPOCHS.

## Conclusion
In this section, I discussed the relative merits of the Naive Bayes and Perceptron algorithms based on their performance on the test dataset. I provided a rationale for choosing one algorithm over the other and discussed the factors that may have contributed to the observed results.
