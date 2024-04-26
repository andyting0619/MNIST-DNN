# MNIST-DNN
- A deep neural network (DNN) for MNIST classification.
# Project Overview
- The goal of this project is to train a deep neural network (DNN) to recognize and classify handwritten digits from the MNIST dataset.
# Requirement
- Python 3.8 or higher
# How to Use the Model
1. Download and extract the files.
2. Copy and paste the `model.pth` file into your working directory.
3. Run the command prompt as an administrator.
4. Install PyTorch using the following command:

   ```
   pip install torch

5. Open a new .ipynb file in your working directory, then import PyTorch by executing the following code:

   ```
   import torch

6. Load the model by executing the following code:

   ```
   model = torch.load("model.pth")

7. Turn the model into evaluation mode for inference:

   ```
   model.eval()

8. Use the model to predict on your dataset:

   ```
   predictions = model(dataset)
