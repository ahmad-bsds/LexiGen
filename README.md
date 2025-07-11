# LexiGen 🧠✨  
**Autoregressive Character-Level Language Model for Word Generation**

LexiGen is a character-level bigram and MLP-based language model inspired by Andrej Karpathy’s [makemore](https://github.com/karpathy/makemore). It is built and trained entirely in a Jupyter Notebook for clarity, education, and experimentation. LexiGen generates word-like sequences by learning from text data using deep learning techniques like backpropagation, embeddings, and multilayer perceptrons (MLPs).

---

### Sample Names generated
```txt
junido.
josalie.
part.
arold.
andie.
leonora.
juen.
burneta.
ernia.
vicie.
boninroie.
lessie.
evy.
arte.
farmunthia.
etma.
rosia.
lean.
jani.
core.
yse.
orett.
janith.
jomiif.
wynn.
sana.
saris.
iro.
sushaddis.
mattie.
```
  
## 📂 Notebook Structure

### **1. Data**
- Load and inspect a custom text dataset (e.g. names, words).
- Understand character distribution.

### **2. Explore Data**
- Frequency analysis.
- Vocabulary creation.
- Mapping characters to integers.

### **3. Preprocessing**
- Encode sequences.
- Prepare training and validation splits.

---

## 🔍 Prediction Techniques

### **4. Predicting a Word**
- Generate word samples based on initial seed characters.

### **5. Predict Using Bigram Probabilities**
- Predict next character using a bigram lookup table.

### **6. Uniform Sampling**
- Generate words using a uniform distribution for comparison.

### **7. N-gram Probabilities**
- Incorporate more context for better prediction accuracy.

---

## 🧪 Evaluation & Training

### **8. Evaluation**
- Measure model performance using cross-entropy loss.

### **9. Loss Function**
- Implement negative log-likelihood loss manually and with PyTorch.

---

## 🧠 Modeling

### **10. Smoothing Techniques**
- Address zero-probability issues in sparse bigram tables.

### **11. Bigram Character-Level Model**
- Train a lookup-table model with backpropagation.

### **12. Backpropagation**
- Implement manual gradient descent on a bigram model.

---

## ⚙️ Neural Network (MLP)

### **13. MLP Dataset Setup**
- Format inputs and labels for MLP model training.

### **14. Embedding Table**
- Introduce learnable embeddings for characters.

### **15. Weights & Architecture**
- Define model layers, activation functions, and initialization.

### **16. Managed Code**
- Refactor training into functions for cleaner workflow.

### **17. Full Dataset MLP**
- Train MLP on full dataset, compare performance.

### **18. Optimization**
- Explore learning rates, loss trends, and training dynamics.

---

## 🔬 Experiments

### **19. Scaling the Model**
- Increase model capacity: hidden layers and neurons.

### **20. Tuning Neurons**
- Find optimal neuron count for generalization.

### **21. Batch Size Effects**
- Compare small vs. large batch performance.

---

## 🎲 Sampling From Model

### **22. Sampling Techniques**
- Temperature scaling.
- Top-k and greedy sampling.

---

## 🛠️ Issues Explored

- **Initialization Pitfalls**
- **Kaiming Initialization**
- **Batch Normalization**

---

## 📌 Features

- ✅ Bigram Language Modeling
- ✅ MLP Neural Network Implementation from Scratch
- ✅ Manual Backpropagation and Loss Evaluation
- ✅ PyTorch for High-Level Abstractions
- ✅ Data Sampling and Evaluation
- ✅ Model Scaling and Hyperparameter Tuning
- ✅ Visual & Code-Driven Analysis in Jupyter Notebook

---

## 🚀 Getting Started

1. Clone the repo or download the notebook:
   ```bash
   git clone https://github.com/yourusername/lexigen.git](https://github.com/ahmad-bsds/LexiGen.git
