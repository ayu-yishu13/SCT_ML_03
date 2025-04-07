# SCT_ML_01
Skill Craft task01

# 🐱🐶 Cat vs Dog Image Classifier using SVM

This project is a simple image classifier that distinguishes between cats and dogs using a Support Vector Machine (SVM) model trained on image data.

## 📁 Project Structure

📦 SCT_ML_01/ ├── 01_preprocessing.ipynb # Preprocessing images and training the model ├── model/ │ ├── X.npy # Features │ ├── y.npy # Labels │ └── svm_model.pkl # Trained SVM model ├── .gitignore └── README.md # You're here!


## 🔍 How it Works

- Converts images of cats and dogs into 256x256 grayscale format.
- Flattens image data and feeds it to an SVM classifier.
- Saves the model and NumPy arrays for later use.

## 📦 Requirements

Install dependencies using pip:

```bash
pip install numpy scikit-learn opencv-python

🚀 How to Run
Run the preprocessing + training notebook:

bash
Copy
Edit
01_preprocessing.ipynb
Ensure you have a data/ directory with cat/ and dog/ subfolders.

🧠 Model Details
Model: Support Vector Machine (SVM)

Accuracy: ~92% (depending on dataset and preprocessing)

Image Size: 256x256

📌 Notes
This repo uses .npy files to avoid retraining the model every time.

Consider using Git LFS if your model files get too large.

❤️ Contributions
Feel free to fork and improve! Pull requests are welcome 😊



