# Facial Emotion Recognition System

This project is a facial emotion recognition system designed to classify emotions using high-resolution image data. The system is trained on the AffectNet dataset and leverages various machine learning and computer vision libraries.

---

## Dataset: AffectNet
The training data used for this project is the AffectNet dataset. 

- **Official Website**: [AffectNet](http://mohammadmahoor.com/affectnet/)
- **Dataset Access**: Students must have their advisors submit a request for access using the following form: [AffectNet Request Form](http://mohammadmahoor.com/affectnet-request-form/).

---

## Dependencies

The project requires the following libraries and frameworks:
- **Python 3.x**
- **numpy**
- **matplotlib**
- **pandas**
- **os** (Standard Library)
- **tensorflow**
- **scikit-learn**
- **Pillow (PIL)**
- **OpenCV (cv2)**
- **seaborn**

Ensure that all dependencies are installed before running the notebook. You can install the required libraries using `pip`:

```bash
pip install numpy matplotlib pandas tensorflow scikit-learn pillow opencv-python seaborn
```

---

## How to Run

1. **Download the Dataset**:
   - Submit a request for access to the AffectNet dataset and download the data after receiving approval.

2. **Prepare the Data**:
   - Untar the dataset and organize it as required by the notebook. Make sure to specify the dataset path in the relevant section of the notebook.

3. **Run the Notebook**:
   - Open the notebook (`Main.ipynb`) in Jupyter Notebook or JupyterLab.
   - Execute the cells in sequence to preprocess the data, train the model, and evaluate performance.

4. **Output**:
   - The notebook will generate metrics and visualizations to evaluate the model's performance.

---

## Notes

- This system uses **TensorFlow** for training the deep learning model.
- Pre-trained models and transfer learning techniques may be used to improve performance.
- Testing for biases across different classifications within the dataset is included.

---


