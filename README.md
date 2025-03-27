# 🧠 Pneumonia Detection Using CNN — A Deep Learning Approach to Save Lives

### Fine-tuned Convolutional Neural Network for early-stage pneumonia detection in Sub-Saharan Africa

---

## 📌 Project Overview

Pneumonia is the leading infectious cause of death in children under 5 — particularly in **Sub-Saharan Africa**, where early detection tools are often lacking due to resource constraints.

This project presents a **fine-tuned Convolutional Neural Network (CNN)** model trained on chest X-ray data to accurately and quickly detect pneumonia. Originally built as part of an academic deep learning course, the model was improved through **parameter tuning and data augmentation** to maximize performance.

> 🎯 **Goal:** Create a low-cost, high-accuracy model for early pneumonia detection, deployable in rural or underserved areas.

---

## 🧪 Problem

In many regions of Africa, pneumonia goes undiagnosed until it’s too late. The Gates Foundation and similar organizations aim to solve problems like these at scale — but they require affordable, scalable, and deployable AI solutions.

---

## 🧠 Model Details

- **Base Model**: Provided CNN architecture
- **Tuning Applied**: Batch size, learning rate, dropout rates
- **Techniques Used**:  
  - Data augmentation (flipping, rotation, rescaling)  
  - Early stopping  
  - Regularization  
  - Epoch tuning  
- **Evaluation Metrics**:  
  - ✅ Accuracy: `~95.6%`  
  - ✅ AUC: `~98.75%`  
  - ✅ Recall: High sensitivity to positive cases (crucial for early detection)

---

## 🗂️ Repository Contents
```
cnn-pneumonia-detection/ ├
── cnn_pneumonia.ipynb # Notebook with full model tuning & metrics 
├── cnn_pneumonia.html # Rendered version of notebook 
├── DeepLearningUganda.pdf # Final project slides 
├── pneumonia_memo.pdf # Impact memo pitched to the Gates Foundation 
├── README.md # You are here
```


---

## 📄 Memo to the Gates Foundation

Included in this repo is a brief proposal outlining the **moral and operational case** for deploying this AI tool to help screen children in rural clinics.

> _"Even a 20% reduction in late pneumonia detection could save tens of thousands of lives annually. With fine-tuned, open-source CNN models, this isn’t science fiction — it’s deployment-ready reality."_  
> — *Memo to the Gates Foundation*

---

## 📊 Results Preview

> AUC: **0.9875**  
> Accuracy: **95.6%**  
> Confusion matrix shows strong true positive rate for pneumonia cases.

---

## 🛠️ How to Run

1. Clone the repo
2. Open `cnn_pneumonia.ipynb` in Jupyter or VS Code
3. Run all cells (data is loaded from Kaggle or local directory)
4. Review the model outputs, ROC curve, and training logs

---

## 👨‍💻 Author

**Asad Adnan**  
Master’s in Business Analytics, University of Notre Dame  
*Bringing deep learning to public health — one model at a time.*

📫 [LinkedIn](https://www.linkedin.com/in/asadadnan)  
📧 Email: asad@example.com *(update this if you're publishing)*

---

## 🤝 Acknowledgments

- Instructor-provided base CNN architecture
- Kaggle dataset on pediatric pneumonia X-rays
- Guidance from peers and mentors at the University of Notre Dame

---

## 🧭 Future Directions

- Integrate into a **mobile diagnostic app**
- Validate performance on **real-world clinical images**
- Extend the model to **multi-disease classification** (e.g. TB, Covid, asthma)
- Partner with NGOs for **pilot deployment in Uganda or Nigeria**

---

## 📢 License & Ethical Use

This model is built for **research and humanitarian purposes** only. Not to be used in place of certified clinical diagnosis without regulatory approval.

