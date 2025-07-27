# Kidney-Stone-Detection

This project focuses on detecting kidney stones using multi-modal fusion techniques that combine data from CT scans and ultrasound images. The notebook explores various stages of the pipeline, including data preprocessing, augmentation, model development, and evaluation.

## Notebook Overview

1. **Data Sources**:
   - CT Scan Dataset: Includes original and augmented images for kidney stone detection.
   - Ultrasound Dataset: Contains images categorized as "Stone" and "No Stone."

2. **Data Preprocessing**:
   - Stratified splitting of datasets into training, validation, and test sets.
   - Image augmentation to enhance model generalization.

3. **Model Development**:
   - **CT Scan Model**: Built using InceptionV3 for feature extraction.
   - **Ultrasound Model**: Built using a hybrid CNN-LSTM architecture.
   - **Fusion Model**: Combines features from both modalities using a concatenation-based approach.

4. **Evaluation**:
   - Metrics such as accuracy, F1 score, and confusion matrix are used to evaluate the models.
   - Visualization of training and validation performance.

5. **Model Saving**:
   - The trained fusion model is saved for future use.

## Further Contributions

Contributions to this project are welcome! Here are some ways you can contribute:
- **Dataset Expansion**: Add more diverse datasets to improve model robustness.
- **Model Optimization**: Experiment with different architectures or hyperparameters.
- **Explainability**: Implement techniques like Grad-CAM to visualize model decisions.
- **Deployment**: Develop a web or mobile application for real-time kidney stone detection.
- **Documentation**: Enhance the documentation for better clarity and usability.

Feel free to fork the repository and submit a pull request with your improvements!
