---

# Brain Tumors Classification Using CNN

## Overview

This project focuses on the classification of brain tumors using Convolutional Neural Networks (CNN) on MRI images. Brain tumors are abnormal cell masses in the brain that can be either benign (noncancerous) or malignant (cancerous). Early detection and accurate classification are crucial for effective treatment.

## What are Brain Tumors?

A brain tumor is a collection or mass of abnormal cells in the brain. The skull, which encases the brain, is rigid, and any growth within this limited space can cause problems. Brain tumors can be either cancerous (malignant) or noncancerous (benign). As these tumors grow, they can increase the pressure inside the skull, leading to brain damage and potentially life-threatening conditions.

## Methods

Deep learning techniques, particularly CNNs, have shown promising results in improving health diagnosis accuracy. This project employs a CNN-based multi-task classification approach to:

- Detect the presence of brain tumors.
- Classify the tumor type and grade based on MRI images.
- Identify the tumor location through segmentation.

Instead of using separate models for each classification task, this project leverages a single CNN model to perform multiple classification tasks, making the approach more efficient and unified.

## Dataset

- **Source**: [Kaggle - Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/)
- **Description**: The dataset contains 7022 MRI images of the human brain, classified into four categories:
  - Glioma
  - Meningioma
  - No Tumor
  - Pituitary

- **Data Imbalance**: The dataset is imbalanced, with varying numbers of images in each category. To address this, data augmentation techniques were applied to increase the variation and balance the dataset.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Martinexe4/brain-tumor-classification.git
   cd brain-tumor-classification
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it in the appropriate directory.

## Results

The CNN model successfully classifies brain tumors into the four categories with high accuracy. Detailed performance metrics and visualizations of the results can be found in the `results` directory.

## Conclusion

This project demonstrates the potential of deep learning, specifically CNNs, in the field of medical image analysis. By accurately classifying brain tumors, this model can assist medical professionals in diagnosing and treating patients more effectively.

## Future Work

- Implement more advanced data augmentation techniques to further improve model robustness.
- Experiment with different CNN architectures to enhance model performance.
- Explore the use of transfer learning for better generalization on smaller datasets.

## Acknowledgements

- The dataset used in this project is provided by [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).
- Thanks to the open-source community for the tools and libraries that made this project possible.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

