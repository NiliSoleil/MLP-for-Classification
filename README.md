# MLP-for-Classification
**Deep Learning Project: Multilayer Perceptron - Binary Classification**

This repository contains a class project implementing and training a Multilayer Perceptron (MLP) for a **Binary Classification** task. 

**Project Overview:**
The **goal** of this class project was to:
  1️⃣ Prepare the dataset (Death Event) for a deep learning model.
  2️⃣ Define and train a simple Multilayer Perceptron (MLP).
  3️⃣ Analyze the model's performance and key parameters.
  4️⃣ Experiment with various hyperparameters and device configurations.
  
**Project Structure and Key Steps:**
The project was completed in the following stages:
  **1. 📊 Dataset Preparation:** The dataset was loaded and preprocessed as needed. It was split into training (80%) and validation (20%) sets. Then a DataLoader was used to create mini-batches for efficient training. The initial batch size was set to 4.
  **2. 🧠 Neural Network Model Definition:** A suitable Multilayer Perceptron (MLP) model was defined. The SGD optimizer and an appropriate loss function were used. The initial bias values of the last layer were printed to compare with the final trained values.
  **3. ⚙️ Device Configuration:** The model was moved to a GPU for faster training. The GPU type used in the Colab environment was identified and printed.
  **4. 🏋️ Model Training:** The standard training loop for deep learning models was implemented. The torchmetrics library was used to calculate accuracy and loss. The total training time was measured and recorded.
  **5. 📈 Analysis and Results:**
     Learning Curve: Plots were generated to show the training and validation loss, as well as accuracy, over each epoch.
     Parameter Analysis: The number of weights and bias parameters in the model were calculated.
     Bias Comparison: The bias values of the last layer were printed after training and compared to their initial values. The change in these values demonstrates the learning process.
  **6. 📥 Model Saving and Loading:** The trained model was saved to a file.The saved model was then loaded to ensure the parameters were preserved.
  **7. 🎯 Model Evaluation:** The loaded model was evaluated on a separate test.csv dataset. The predictions for the test data were saved to a predictions.csv file.
  **8. ✅ Hyperparameter Tuning:**
     Batch Size: Experiments were conducted with different batch sizes (4, 8, 16) to observe their effect on the learning process.
     Learning Rate: The model was trained with different learning rates (0.1, 0.01, 0.001).
     Activations: The performance of different activation functions (ReLU, Leaky ReLU, GELU) was compared.
     CPU vs. GPU: The training time was compared between CPU and GPU to demonstrate the performance gain from using a GPU.
     
**How to Run the Code**
  🛠️**Prerequisites:** Make sure you have PyTorch and other necessary libraries installed.
  🖥️**Run the Notebook:** The code is available in ..... You can run it in Google Colab or any Jupyter environment.

Author: Niloufar Soleil
 
