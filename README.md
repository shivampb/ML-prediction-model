# ML-prediction-model![X](https://github.com/shivampb/ML-prediction-model/assets/129358564/658653e1-d6ad-40be-9d0b-536c13efdd6c)
The image illustrates the process of training and testing a machine learning model using a dataset split into training and testing sets. Here's an explanation of the process in technical terms:

### 1. Dataset Preparation:
The dataset is represented by two components:
- **X (Features)**: This is the input data consisting of numerical or categorical features used to predict the target variable.
- **Y (Target)**: This is the output data representing the target labels or classes that the model aims to predict.

### 2. Train-Test Split:
The dataset is divided into two parts:
- **80% Train Set**: This portion of the data is used to train the machine learning model. It includes 80% of the original data points from both the features (X) and the target labels (Y).
  - In the image, the training set is highlighted and contains rows of feature values (like `23 1`, `25 1`, etc.) paired with corresponding target labels (like `hiphop`, `jazz`, etc.).
  
- **20% Test Set**: This portion is set aside to evaluate the performance of the trained model. It consists of the remaining 20% of the data points.
  - The test set is highlighted separately and contains feature values (like `27 0`, `30 0`, etc.) and the corresponding target labels (like `acoustic`, `classical`, etc.).

### 3. Model Training:
- The training set (80% of the data) is fed into a machine learning algorithm to train the model. During this phase, the model learns patterns and relationships between the input features (X) and the target labels (Y).
  - This step is indicated by the arrow labeled "FEED THIS TO MODEL FOR TRAIN".

### 4. Model Testing:
- Once the model is trained, the test set (20% of the data) is used to evaluate its performance. The model makes predictions on the test features (X_test), and these predictions are compared with the actual target labels (Y_test) to calculate metrics such as accuracy, precision, recall, etc.
  - This step is shown by the arrow labeled "USING BOTH TO MAKE ACCURACY OF OUR MODEL".

### Summary:
1. **Splitting the Data**: The data is split into training (80%) and testing (20%) sets.
2. **Training the Model**: The training set is used to train the model.
3. **Evaluating the Model**: The test set is used to evaluate the model's performance.

This process ensures that the model is tested on unseen data, providing a measure of how well it generalizes to new data.
