# 🍽️ Calorie Prediction using Nutrition5k Dataset

## 📖 Overview
This project predicts the **calorie content of food images** using deep learning and the **Google Nutrition5k dataset**.  
It applies **computer vision and regression-based learning** to estimate nutritional values directly from food images, aiming to make nutrition tracking more convenient and data-driven.

---

## 💡 Problem Statement
Manual calorie tracking is often time-consuming and inaccurate.  
This project explores how **AI models can automatically estimate calories** from meal photo

---

## ⚙️ Approach
1. **Dataset** – Google’s **Nutrition5k** dataset (over 5,000 meals with nutritional annotations).  
2. **Preprocessing** – Image resizing, normalization, and splitting into train/validation sets.  
3. **Model** – A **CNN-based regression model** trained to predict calorie values.  
4. **Training** – Optimized using **Mean Squared Error (MSE)** loss with the **Adam** optimizer.  
5. **Evaluation** – Measured with **MSE** and **MAE** metrics on the validation set.

---

## 📊 Results
| Metric | Value |
|---------|--------|
| **Validation Loss (MSE)** | **13811.30** |
| **Validation MAE** | **87.37** |

The results show that the model can capture meaningful calorie patterns from food images, though there’s scope for improving precision using advanced architectures and data augmentation.

---

## 🧩 Tech Stack
- **Python**
- **TensorFlow / Keras**
- **NumPy, Pandas, Matplotlib**
