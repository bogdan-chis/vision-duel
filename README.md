# 🤖 Vision Duel

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

Vision Duel is a **Jupyter Notebook**–powered showcase comparing two Convolutional Neural Network (CNN) architectures—an in-house custom build vs. classic AlexNet—across the CIFAR-10 and MNIST datasets. Dive into full data preprocessing, targeted augmentations, training/validation curves, confusion matrices, and performance insights! 🎯

---

## 🔍 What’s Inside

- **Data Preprocessing**  
  - Load & clean CIFAR-10 & MNIST  
  - Normalize, reshape & batch preparation  
- **Data Augmentation**  
  - Rotation, shifting, flipping & more  
  - Targeted augmentation experiments  
- **Model Architectures**  
  - 🛠️ Custom CNN: from-scratch layers & blocks  
  - ⚡ AlexNet: classic benchmark implementation  
- **Training & Validation**  
  - Epoch-by-epoch loss & accuracy curves  
  - Early stopping & learning-rate scheduling  
- **Evaluation Metrics**  
  - 📊 Confusion matrices per class  
  - 🎯 Accuracy, precision, recall, F1-score  
- **Comparison & Analysis**  
  - Side-by-side performance plots  
  - Discussion of trade-offs & insights  

---

## 🚀 Quick Start

1. **Clone the repo**  
   ```bash
   git clone https://github.com/bogdan-chis/vision-duel.git
   cd vision-duel
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**  
   ```bash
   jupyter notebook Vision-duel.ipynb
   ```  
   - Execute cells sequentially to preprocess data, train models, and view results.  
   - Customize augmentation parameters or network hyperparameters on the fly!  

---

## 📊 Key Highlights

- **Dual-Model Comparison**: Understand how a minimal custom CNN stacks up against AlexNet.  
- **Visual Analysis**: Training/validation plots + confusion matrices for deep insights.  
- **Augmentation Experiments**: See the impact of targeted augmentations on model robustness.  
- **Modular Notebook**: Easily adapt to your own datasets or networks.  

---

## 🛣️ Roadmap

- 🔄 Add transfer-learning experiments (e.g., ResNet, VGG)  
- 📈 Integrate tensorboard for live dashboarding  
- 🌐 Export results into a lightweight Flask/Streamlit app  

---

## 📄 License

This project is MIT-licensed — see the [LICENSE](LICENSE) file for details.

---

*Let the duel begin!* ⚔️✨
