# 📧 HamOrSpam

This project implements a binary text classification model to detect **spam** messages from SMS texts. It uses TensorFlow and Keras, with a text vectorization layer and a simple neural network.

---

## 🚀 Project Overview

The model is trained on a public SMS dataset with two classes: **ham** (not spam) and **spam**. It preprocesses text using TensorFlow's `TextVectorization` and trains a neural network with embedding, pooling, and dense layers.

---

## 📊 Training Details

The model was trained for **10 epochs** with the following performance:

| Epoch | Training Accuracy | Training Loss | Validation Accuracy | Validation Loss |
|-------|-------------------|---------------|---------------------|-----------------|
| 1     | 85.70%            | 0.4215        | 86.57%              | 0.3639          |
| 2     | 86.84%            | 0.3567        | 86.57%              | 0.3326          |
| 3     | 86.98%            | 0.3002        | 94.54%              | 0.1860          |
| 4     | 94.90%            | 0.1454        | 96.34%              | 0.1055          |
| 5     | 97.99%            | 0.0710        | 96.41%              | 0.1002          |
| 6     | 97.67%            | 0.0821        | 97.63%              | 0.0930          |
| 7     | 98.59%            | 0.0514        | 96.84%              | 0.1003          |
| 8     | 98.70%            | 0.0432        | 97.49%              | 0.0757          |
| 9     | 99.03%            | 0.0350        | 97.84%              | 0.0579          |
| 10    | 99.22%            | 0.0297        | 98.20%              | 0.0630          |

---

## 🧪 Example Prediction

**Input:**  
`pred_text = "how are you doing today?"`

**Model output:**  
- Spam Probability: 0.0196
- Predicted Label: ham

---
## 🛠️ How to Use

1. Clone this repository.

2. Install dependencies:

   ```bash
   pip install tensorflow tensorflow-datasets pandas matplotlib

3. Run the training script to train the model on the SMS dataset.

4. Use the model to predict if an SMS is spam or ham.
   
---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---
This project is part of the freeCodeCamp Machine Learning with Python certification. 🎓
