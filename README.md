# DeepSeaVision 🌊

A deep learning-based marine life detection and classification system that detects and classifies marine species from underwater images using Convolutional Neural Networks (CNNs).

---

## 📌 Overview

DeepSeaVision is built to assist in the identification of marine life from underwater images using computer vision techniques. This can help researchers, conservationists, and marine biologists efficiently analyze large volumes of underwater visual data.

---

## 📁 Project Structure

```
DeepSeaVision/
│
├── data/               # Dataset (underwater images)
├── models/             # Trained model weights
├── notebooks/          # Jupyter notebooks for experiments
├── src/                # Core source code
│   ├── data_loader.py      # Data preprocessing and loading
│   ├── model.py            # CNN model architecture
│   ├── train.py            # Model training logic
│   └── inference.py        # Inference code
├── results/            # Output predictions and sample results
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

---

## 💻 Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/ARYABARAI30123/DeepSeaVision.git
cd DeepSeaVision
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

3. **Train the model:**
```bash
python src/train.py
```

4. **Run inference on test images:**
```bash
python src/inference.py
```

---

## 🔍 Sample Output

You can find sample predictions in the `results/` directory after running inference.

---

## 👤 Author

**Arya Barai**  
GitHub: [@ARYABARAI30123](https://github.com/ARYABARAI30123)

---

