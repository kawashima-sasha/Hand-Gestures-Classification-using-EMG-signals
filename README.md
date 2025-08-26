# Hand-Gestures-Classification-using-EMG-signals
EMG signal classification system using machine learning and deep learning to recognize and classify hand gestures using EMG signals from MYO Thalmic bracelet data.

## Dataset
- 8-channel EMG data from 36 subjects
- 6 different hand gestures recorded twice per subject
- MYO Thalmic bracelet sensor data

## Approach
- **Preprocessing**: Signal cleaning, feature extraction (RMS, ABS_diff)
- **Machine Learning**: 4 different models with hyperparameter optimization
- **Deep Learning**: Sequential neural network with Adam optimizer
- **Training/Testing**: 70/30 split

## Results
- **Best Accuracy**: 90.6%
- **Model**: Deep learning approach with 48-neuron dense layers
- **Loss**: 28.4%

## Technologies
- Python
- scikit-learn, TensorFlow/Keras
- NumPy, Pandas
- Signal processing libraries
