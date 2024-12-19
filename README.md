# Milestone Project 1: Food Vision Big

**Description**  
This project utilizes TensorFlow and EfficientNet to create a deep learning model for classifying food images into 101 categories. It employs mixed precision training for efficiency and explores fine-tuning techniques to enhance model accuracy. This project demonstrates key aspects of working with deep learning, including data preprocessing, feature extraction, and model fine-tuning.

---

## Features

- Food image classification using EfficientNetB0.
- Mixed precision training for improved performance.
- Fine-tuning for better model accuracy.
- Model performance evaluation with metrics like loss and accuracy.
- TensorBoard integration for tracking training progress.

---

## Dataset

The dataset consists of 101 food categories with high-quality labeled images. For reproducibility, the project provides steps to download and preprocess the dataset.

---

## Requirements

- Python 3.7+
- TensorFlow
- NumPy
- Matplotlib
- Google Colab (optional, for running the notebook)

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ShreCodes2809/food_vision.git
   cd Food-Vision-Big
   ```
2. Download the dataset and place it in the appropriate directory.
3. Run the Jupyter Notebook to train and evaluate the model:
   ```bash
   jupyter notebook Milestone_Project_1_Food_Vision_Big.ipynb
   ```

---

## Workflow

1. **Data Preparation**: Images are resized and normalized for model input.
2. **Feature Extraction**: EfficientNetB0 is used for initial feature extraction with pre-trained weights.
3. **Fine-Tuning**: Additional layers are unfrozen to fine-tune the model with a lower learning rate.
4. **Evaluation**: The model is evaluated on a test set for loss and accuracy.
5. **Results Visualization**: Loss curves are plotted to track training progress.

---

## Results

- Initial model accuracy: ~70.6%
- Fine-tuned model accuracy: ~71.4%
- Loss curves demonstrate improvements over epochs.

---

## Future Work

- Experiment with other EfficientNet versions.
- Optimize preprocessing and data augmentation.
- Explore alternative fine-tuning strategies.

---

## License

This project is licensed under the MIT License.

---
