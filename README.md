# Automated Chest X-Ray Classification using Deep Learning and Hybrid Models

## Overview
This project automates chest X-ray image classification using deep learning (DL) and hybrid models. It leverages MobileNet for feature extraction and a Support Vector Machine (SVM) for classification, providing an efficient and accurate solution for medical image analysis.

## Key Features
- **Preprocessing & Augmentation**: Enhances image quality and improves model performance.
- **MobileNet Model**: A lightweight deep learning model for feature extraction.
- **Hybrid Approach (MobileNet + SVM)**: Combines deep learning with traditional machine learning for better classification accuracy.
- **Efficient Training**: Uses transfer learning to reduce training time.

## How It Works
1. **Data Preprocessing**: Normalization and augmentation techniques are applied to enhance image quality.
2. **Feature Extraction**: MobileNet extracts relevant features from X-ray images.
3. **Classification**: The extracted features are passed to an SVM model for classification.
4. **Evaluation**: The model is tested for accuracy, precision, and recall.

## Setup & Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/vaisnavrr/chest-xray-classification.git
   cd chest-xray-classification
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```sh
   jupyter notebook CXR_Hybrid_Model.ipynb
   ```

## Results
The hybrid model enhances accuracy compared to standalone deep learning models by leveraging the strengths of both MobileNet and SVM.

## Contributions
Feel free to contribute by improving the code, adding new models, or enhancing the dataset.

## License
This project is open-source under the MIT License.

