# speech-emotion-recognition

This project focuses on detecting and classifying human emotions from speech audio using machine learning. By extracting features from voice recordings and applying classification algorithms, the system identifies emotions like happy, sad, angry, and more.

🎯 **Objective**

To build a machine learning pipeline that recognizes human emotions based on speech signals by:

Preprocessing audio data

Extracting relevant features (MFCC, chroma, etc.)

Training and evaluating emotion classification models

📁 **Dataset**

Dataset Used: RAVDESS – Ryerson Audio-Visual Database of Emotional Speech and Song

Emotions Covered:

Neutral

Calm

Happy

Sad

Angry

Fearful

Disgust

Surprised

🧰 **Technologies Used**

Python (Jupyter Notebook / Google Colab)

Libraries:

librosa – Audio processing

numpy, pandas – Data handling

matplotlib, seaborn – Visualization

scikit-learn – Model building (SVM, MLP, Random Forest, etc.)

🧪 **Feature Extraction**

Key features used from audio signals:

MFCC (Mel Frequency Cepstral Coefficients)

Chroma features

Mel Spectrogram

Zero Crossing Rate

Spectral Contrast

🧠 **Model Training**

Data split into training and testing (e.g., 80/20)

Trained multiple classifiers (SVM, MLP, Random Forest)

Evaluated using metrics like accuracy, precision, recall, F1-score

📊 ** Results**

| Model         | Accuracy |
| ------------- | -------- |
| SVM           | 75%      |
| MLPClassifier | 80%      |
| Random Forest | 78%      |

📈 **Visualizations**

Confusion Matrix

Emotion distribution plots

Feature importance plots
