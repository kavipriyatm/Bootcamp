# README

## Task 1: Basic Digit Classification

### What I Learned:
- Implemented a basic digit classification model.
- Flattened 28x28 images into 784 inputs.
- Used one-hot encoding for labels.
- Defined a Sequential model with Softmax activation.
- Compiled with categorical crossentropy loss and RMSprop optimizer.
- Trained for 10 epochs and plotted loss/accuracy curves.

### Challenges Faced:
- Handling image preprocessing and normalization.

### Dataset Used:
- **Name:** Digit Recognizer Dataset
- **Source:** Kaggle

---

## Task 2: Batch Size Tuning

### What I Learned:
- Trained with batch sizes of 1000 and 2000.
- Observed stability improvements with larger batch sizes.
- Compared loss and accuracy curves for different batch sizes.

### Challenges Faced:
- Managing computational efficiency with large batch sizes.

### Dataset Used:
- **Name:** Digit Recognizer Dataset
- **Source:** Kaggle

---

## Task 3: Optimizer Adjustment

### What I Learned:
- Compared AdaDelta and Adam optimizers.
- Trained for 20 epochs with different learning rates.
- Observed improved stability and convergence with Adam.

### Challenges Faced:
- Selecting appropriate learning rates for optimizers.

### Dataset Used:
- **Name:** Digit Recognizer Dataset
- **Source:** Kaggle

---

## Task 4: Hidden Layer Addition

### What I Learned:
- Introduced a hidden layer (50 units, ReLU) for improved learning capacity.
- Trained for 20 epochs and compared performance to baseline.
- Observed increased accuracy and potential overfitting.

### Challenges Faced:
- Balancing model complexity to avoid overfitting.

### Dataset Used:
- **Name:** Digit Recognizer Dataset
- **Source:** Kaggle

---

## Summary
These tasks helped me understand digit classification, batch size effects, optimizer impact, and hidden layer benefits in deep learning.
