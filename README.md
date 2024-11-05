# CNN Tutorial Notebooks for High School Education: Machine Learning and Data Mining

These Google Colab notebooks were developed in 2022 as part of the “Machine Learning and Data Mining” practical course for high school students, prepared under the SW-centered University Project of SKKU funded by the Ministry of Science and ICT and the Institute for Information and Communications Technology Planning and Evaluation (IITP).

## Target Audience
- Beginners with basic knowledge of Python and the PyTorch framework
- Learners with a theoretical understanding of deep learning training and inference processes
- Those interested in visualizing model accuracy changes and test results during training

## Exercises

### Exercise 1: Fashion MNIST Classification with Custom CNN Model
- **Goal**: Learn data loading using the `torchvision.datasets` FashionMNIST dataset, with a 9:1 train-validation split.
- **Topics**:
  - Building convolutional layers in PyTorch (`torch.nn`) and matching input/output tensor shapes
  - Using cross-entropy loss and Adam optimizer, comparing them with stochastic gradient descent
  - Training a basic CNN, observing loss and accuracy, and visualizing test results with `matplotlib`
- **Purpose**: Introduces CNN basics with a simple dataset and code explanations for students new to Python and PyTorch.

### Exercise 2: Cat & Dog Classification with Custom CNN Model / ResNet18
- **Goal**: Guide students through downloading and using the Cat-and-Dog dataset from Kaggle, creating custom datasets, and exploring binary classification.
- **Topics**:
  - Handling custom datasets with `torch.utils.data.Dataset`, assigning binary labels
  - Managing overfitting through data augmentation and early stopping
  - Building a custom CNN and comparing its performance on complex data with `ResNet18` from `timm`
- **Purpose**: Enables students to apply learned concepts by building and testing their own CNN on real-world data.

### Exercise 3: DeepFake Detection with ResNet18 Model
- **Goal**: Use a small sample from the FaceForensic++ DeepFake dataset for classifying fake vs. real videos.
- **Topics**:
  - Mounting Google Drive in Colab for data access
       - Data source: https://drive.google.com/file/d/1AIJG9i5zGq5kqn8XYcvibytX8ZafvDYD/view?usp=sharing
       - Download `DeepFake.zip` and place it under the `dataset` folder in your Google Drive
  - Building a classifier for fake and real samples based on previous session concepts
- **Purpose**: Prepares students for real-world dataset management and practical classification techniques.
