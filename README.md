# Deep Learning Module Assignment

## 📘 About the Assignment

This assignment involves designing, training, and tuning a **Multilayer Perceptron (MLP)** to classify data points in a challenging **3-class spiral dataset**. The dataset is synthetically generated and poses a complex decision boundary, making it a great task for deep learning experimentation.

### 🔍 Objective

- Build and train an MLP from scratch or using a deep learning framework.
- Handle noisy, non-linearly separable data with custom model design.
- Tune hyperparameters to achieve strong generalization and performance.

### 📊 Dataset Details

- **Classes**: 3
- **Points per class**: 200
- **Input features**: 2D points (X, Y)
- **Noise level**: 0.4

The dataset is generated using a sinusoidal spiral function with added Gaussian noise to increase difficulty.

---

## ⚙️ What I Implemented

### ✅ 1. Data Preparation

- Generated spiral dataset using provided NumPy code.
- Split data into training and test sets (80%-20% split).
- Visualized the dataset using `matplotlib` with class-wise coloring.

### ✅ 2. Model Building (MLP)

- Built an MLP using PyTorch (or another framework if applicable).
- Experimented with:
  - Different numbers of hidden layers (2–3 layers tested)
  - Varying number of neurons per layer (16–128)
  - Activation functions (ReLU, Tanh)
  - Optimizers (SGD, Adam)
  - Learning rates (0.001–0.1)
- Trained for 300–500 epochs
- Implemented early stopping or regularization to prevent overfitting

### ✅ 3. Evaluation

- Plotted training and validation loss/accuracy curves.
- Visualized model decision boundaries on the spiral dataset.
- Analyzed the final performance on the test set.

### ✅ 4. Reflection Questions (answered in the notebook)

- **Model Design Choices**: Discussed rationale for choosing hidden layers and neurons.
- **Hyperparameter Tuning**: Compared results with different learning rates and optimizers.
- **Overfitting/Underfitting**: Addressed model behavior and applied techniques like dropout or early stopping.
- **Future Improvements**: Suggested ideas like using deeper architectures, normalization, or other data generation techniques.

---

