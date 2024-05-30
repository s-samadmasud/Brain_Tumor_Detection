# Brain_Tumor_Detection

This repository implements a brain tumor detection system using machine learning and deep learning techniques.

## Project Goal

The project aims to develop a model that can accurately classify brain MRI scans as either containing a tumor or being normal. This can assist medical professionals in early diagnosis and treatment planning.

## Dependencies

* `scikit-learn`: For machine learning algorithms.
* `matplotlib`: For data visualization.
* `pandas`: For data manipulation.
* `seaborn`: For advanced data visualization.
* `opencv-python`: For image pre-processing and manipulation.
* `tensorflow`: The core deep learning framework.
* `keras`: A high-level API built on top of TensorFlow for easier model development.
* `streamlit` (Optional): To create a web app for interactive model deployment (see "Deployment" section below).

## Installation

1. **Clone this repository:**

   ```bash
   git clone [https://github.com/your-username/brain-tumor-detection.git](https://github.com/your-username/brain-tumor-detection.git)

2. **Create a virtual environment:**

   Highly recommended to isolate project dependencies and avoid conflicts. Here's an example using venv (Python 3.3+):
      ```bash
      python -m venv venv
      source venv/bin/activate  # Linux/macOS
      venv\Scripts\activate.bat  # Windows
3. **Activate the virtual environment (commands above)**
4. **Install dependencies:**
      ```bash
      pip install -r requirements.txt
Note: If you don't have a requirements.txt file, create one by listing all the dependencies mentioned above, one per line. 

## Data Acquisition
1. Download the brain MRI dataset from Kaggle: https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection.
2. Extract the downloaded archive.
3. Move the extracted files to the images folder within this repository. Create the images folder if it doesn't exist.


