# 🧠 CNN for Pneumonia Detection in Ugandan Children

A deep learning project leveraging Convolutional Neural Networks (CNNs) to detect pneumonia from chest X-rays — built with the aim to reduce misdiagnosis and mortality in resource-constrained settings like Sub-Saharan Africa.

---

## 🌍 Project Context

Pneumonia is the **leading infectious killer of children under five** in Uganda, responsible for up to **16% of all child deaths**. Despite this, over **400,000 undiagnosed positive cases** go untreated due to **poor diagnostic access**.

This project addresses that gap by fine-tuning a CNN architecture for high-accuracy image-based pneumonia detection. The model was later pitched as a scalable solution for real-world healthcare deployment in Uganda.

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
- 🧾 **Pitch Memo**: [`pneumonia_memo.pdf`](pneumonia_memo.pdf)  
- 🎥 **Presentation Slides**: [`DeepLearningUganda.pdf`](DeepLearningUganda.pdf)

---

## 🏥 Real-World Application: Uganda Deployment

This project was pitched for deployment in Ugandan hospitals, backed by field-specific research and economic analysis.

### Key Proposal Points:
- **Pilot with 3 hospitals**, training staff and validating in-clinic model performance.
- **Full-scale deployment to 50+ rural clinics** with offline functionality.
- **Integration into national healthcare system** for long-term sustainability.

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

## 📌 Future Directions

- Improve class balance through smarter oversampling
- Integrate clinical metadata alongside X-ray imaging
- Build a user-facing diagnostic app for clinics with limited radiologists
- Integrate into a **mobile diagnostic app**
- Validate performance on **real-world clinical images**
- Extend the model to **multi-disease classification** (e.g. TB, Covid, asthma)
- Partner with NGOs for **pilot deployment in Uganda**


## 🤝 Acknowledgments

- Instructor-provided base CNN architecture
- Kaggle dataset on pediatric pneumonia X-rays
- Guidance from peers and mentors at the University of Notre Dame

---

## 📢 License & Ethical Use

This model is built for **research and humanitarian purposes** only. Not to be used in place of certified clinical diagnosis without regulatory approval.

