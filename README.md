# 🐦 Bird Species Recognition using CUB-200 Dataset

This project demonstrates how to process and prepare the [CUB-200-2011](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html) bird dataset for machine learning tasks such as classification. It includes loading image paths, extracting labels from directory names, and creating a custom validation set for training.

---

## 📂 Dataset Overview

The CUB-200-2011 dataset contains 11,788 images across 200 bird species. Each species is stored in a separate folder with its name prefixed by a numeric ID.

Example folder structure:

```
CUB_200_2011/images/
├── 001.Black_footed_Albatross/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── 002.Laysan_Albatross/
│   ├── image1.jpg
│   └── ...
└── ...
```

---

## 🛠 Features

- Extracts image file paths and their corresponding class labels from the folder structure.
- Converts class names to clean label strings (e.g., `001.Black_footed_Albatross` → `Black_footed_Albatross`).
- Creates a train/validation split using `scikit-learn`.
- Prepares labels for future model training or evaluation.

---

## 🚀 How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/bird-recognition.git
   cd bird-recognition
   ```

2. **Install Dependencies**:
   Make sure you have the following Python packages installed:
   - pandas
   - numpy
   - scikit-learn
   - glob
   - Jupyter (optional, for running the notebook)

   Install using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Dataset**:
   Download and extract the CUB-200-2011 dataset from the [official site](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html).

4. **Run the Notebook**:
   Open `bird_recognition.ipynb` in Jupyter and follow the steps for loading images and creating the validation set.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [Caltech-UCSD Birds 200 Dataset](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)
- Python libraries: scikit-learn, pandas, numpy
