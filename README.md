### Cough Classification using Convolutional Neural Networks

---

#### Project Overview:

This project aims to develop a Convolutional Neural Network (CNN) model to classify cough sounds into four categories: Asthma, Pneumonia, Bronchitis, and Pertussis. The motivation behind this project is to provide a tool for healthcare professionals to assist in diagnosing respiratory diseases quickly and accurately, especially in cases where access to specialized medical facilities is limited.

---

#### Dataset:

The dataset used for training and testing the CNN model consists of four audio databases, each containing cough recordings associated with a specific respiratory disease:
1. **Asthma**: Cough sounds from individuals diagnosed with asthma.
2. **Pneumonia**: Cough sounds from individuals diagnosed with pneumonia.
3. **Bronchitis**: Cough sounds from individuals diagnosed with bronchitis.
4. **Pertussis**: Cough sounds from individuals diagnosed with pertussis (whooping cough).

---

#### Solution Path:

1. **Data Collection**: Gathered cough recordings from reliable sources and medical databases, ensuring diverse representation for each disease category.

2. **Data Preprocessing**: Processed the audio files to extract meaningful features such as spectrograms or Mel-frequency cepstral coefficients (MFCCs) to feed into the CNN model.

3. **Model Architecture**: Designed a CNN architecture tailored for audio classification, considering factors like depth, kernel size, and pooling layers to effectively capture hierarchical features from the audio data.

4. **Model Training**: Trained the CNN model using the preprocessed cough data, employing techniques such as data augmentation and cross-validation to enhance generalization.

5. **Model Evaluation**: Evaluated the trained model on a separate test set to assess its performance metrics such as accuracy, precision, recall, and F1-score.

6. **Deployment**: Implemented the trained model into a user-friendly interface, allowing healthcare professionals to upload cough recordings and receive real-time disease classification results.

---

#### Dependencies:

- Python 3.0
- TensorFlow
- Keras
- Librosa (for audio processing)
- NumPy
- Matplotlib

---

#### Usage:

1. Clone the repository:
```bash
git clone https://github.com/your_username/cough-disease-detection-using-CNN.git
```

2. Install dependencies

3. Run the inference script with your cough recordings:
```bash
python classify_cough.py your_cough_recording.wav
```

---

#### Conclusion:

This project showcases the potential of deep learning in healthcare by providing a tool for automated respiratory disease diagnosis based on cough sounds. By accurately classifying cough recordings, this model can aid healthcare professionals in making timely and informed decisions, ultimately improving patient care and outcomes.

--- 

#### Contributors:

- [Pranav Darak](https://github.com/pranavdarak)
- [Co-contributor Name](https://github.com/co_contributor_username)

---

#### License:

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by adding more cough recordings, improving the model architecture, or enhancing the user interface! Your contributions can make a significant impact on improving healthcare accessibility and quality worldwide.
