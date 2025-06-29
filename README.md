# 🧠 CNN for Pneumonia Detection in Ugandan Children

A deep learning project leveraging Convolutional Neural Networks (CNNs) to detect pneumonia from chest X-rays — developed as part of a Gates Foundation pitch simulation for a graduate-level "Monetizing Machine Learning" course, with the aim to reduce misdiagnosis and mortality in resource-constrained settings like Sub-Saharan Africa.

---

## 🌍 Project Context

Pneumonia is a **leading cause of child mortality** in Uganda, contributing significantly to pediatric deaths. Many cases go undiagnosed due to **limited diagnostic access** in rural areas, creating a substantial healthcare gap.

This project addresses that gap by fine-tuning a CNN architecture for high-accuracy image-based pneumonia detection. The analysis included modeling a scalable deployment strategy for potential real-world healthcare implementation in Uganda.

---

## 🧪 Model Highlights

| Model Type        | Accuracy | AUC     | Precision | Recall   |
|-------------------|----------|---------|-----------|----------|
| CNN (Baseline)    | 93.39%   | 98.76%  | 93.42%    | 93.39%   |
| CNN (Final Tuning)| **95.65%** | **98.75%** | **95.67%**  | **95.66%**  |

- Fine-tuned using **data augmentation, batch normalization**, and hyperparameter tuning.
- Performance validated using **confusion matrices**, **ROC-AUC curves**, and **Kaggle test sets**.

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

## 📑 Deliverables

- 📘 **Notebook**: [`cnn_pneumonia.ipynb`](cnn_pneumonia.ipynb)  
- 📄 **HTML Report**: [`cnn_pneumonia.html`](cnn_pneumonia.html)  
- 🧾 **Business Case Memo**: [`pneumonia_memo.pdf`](pneumonia_memo.pdf)  
- 🎥 **Final Presentation**: [`DeepLearningUganda.pdf`](DeepLearningUganda.pdf)

---

## 🏥 Gates Foundation Pitch Simulation: Uganda Deployment

This project was developed as a comprehensive business case and pitched to simulated Gates Foundation stakeholders, backed by field-specific research and economic analysis as part of our "Monetizing Machine Learning" coursework.

### Key Proposal Components:
- **Preliminary pilot program** with 10-15 rural clinics for initial validation and staff training.
- **Modeled scaling strategy** projecting potential reach to thousands of children annually.
- **Cost-benefit analysis** estimating up to 60% cost reduction vs. traditional radiologist diagnosis.

Read the full memo: [`pneumonia_memo.pdf`](pneumonia_memo.pdf)

---

## 🚀 Technologies Used

- Python, Keras, TensorFlow
- Jupyter Notebook
- Matplotlib, Seaborn, scikit-learn
- CNN Architecture for Binary Classification

---

## 👤 Author

**Asad Adnan**  
Master’s in Business Analytics — University of Notre Dame  
*Exploring data-driven solutions in public health, development, and strategy.*

---

## 📌 Future Research Directions

- Improve class balance through smarter oversampling techniques
- Integrate clinical metadata alongside X-ray imaging for enhanced accuracy
- Explore user-facing diagnostic applications for resource-limited settings
- Validate model performance on **real-world clinical datasets**
- Investigate **multi-disease classification** capabilities (TB, Covid, respiratory conditions)
- Research partnership opportunities with NGOs for **potential pilot studies**


## 🤝 Acknowledgments

- Instructor-provided base CNN architecture
- Kaggle dataset on pediatric pneumonia X-rays
- Guidance from peers and mentors at the University of Notre Dame

---

## 📢 License & Ethical Use

This model is built for **research and humanitarian purposes** only. Not to be used in place of certified clinical diagnosis without regulatory approval.

