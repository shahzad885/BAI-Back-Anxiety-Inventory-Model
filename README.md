**Anxiety Level Classification Model**

This project implements a neural network model to classify anxiety levels (Moderate, Severe, Low) based on demographic information and anxiety-related symptoms. The model was trained on a dataset of 14 features and achieved a test accuracy of ~91%.

**📌 Model Overview**

**Input Features (14 total):**

Demographic info (e.g., Gender, Age)

Symptoms (numbness, wobbliness, afraid of worst happening, heart pounding, trembling, etc.)

**Preprocessing:**

Gender and Anxiety Level encoding

StandardScaler used for feature normalization

**Model Architecture:**

Dense layers with ReLU activation

Batch Normalization for stable training

Dropout (0.3) for regularization

Output layer with Softmax (3 classes)

**Training:**

**Optimizer:** Adam

**Loss:** Sparse Categorical Crossentropy

**Epochs:** 100, Batch size: 32

**Test Accuracy:** 91%
