# Animal Image Classification using CNN
## Project Overview
This project aims to classify animal images using a Convolutional Neural Network (CNN). The dataset contains 50 different types of animals, but for this project, we selected 10 animal types: Collie, Dolphin, Elephant, Fox, Moose, Rabbit, Sheep, Squirrel, Giant Panda, and Polar Bear. Each type consists of 650 images. The goal is to forecast the type of animal based on the given image.

## Necessary Libraries
* Numpy: For linear algebra operations.
* Pandas: For data manipulation and processing.
* Cv2: For image-related tasks such as resizing.
* Os: For handling directory operations.
* Matplotlib: For visualizing data.
* Seaborn: For enhanced visualization.
* Sklearn: For splitting the dataset into training and test sets, and for evaluating the model's performance using various metrics.
* TensorFlow: For image processing, model building, and preventing overfitting.

## Project Stages
1. Importing Necessary Libraries: Import required libraries for data handling and model development.
2. Preparing Data: Load and preprocess the data for use in the model.
3. Encoding and Transforming Data: Convert the target labels into a categorical structure suitable for classification.
4. Splitting Data: Divide the dataset into training and testing sets.
5. Data Augmentation: Apply transformations to the images to enhance the model’s ability to generalize.
6. Model Creation: Define the layers and parameters of the CNN model.
7. Early Stopping: Implement early stopping to prevent overfitting during model training.
8. Visualization: Plot the training and testing loss/accuracy graphs to evaluate model performance.
9. Model Evaluation: Test the model’s performance on unseen test images using a confusion matrix.
10. Image Manipulation: Apply purple, yellow, and green filters to test images and observe the model's response.
11. Evaluating Filtered Images: Measure the model's success when working with the manipulated images.
12. Gray World Algorithm: Apply the Gray World Color Constant Algorithm to corrected images.
13. Re-evaluation: Evaluate the model performance again using the corrected images.
14. Comparison: Compare model performance with different types of test images.

## Access the Project
* To access the detailed project and its implementation, please click [here](https://www.kaggle.com/code/abdurrahmangulmez46/global-ai-hub-image-processing-bootcamp-projectt).
