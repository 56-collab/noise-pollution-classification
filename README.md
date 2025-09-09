# Noise-pollution-classification
🎧 NoisePollutionClassifier

This project uses Machine Learning (ML) to detect and classify urban sounds (e.g., car horns, sirens, drilling, etc.) from the UrbanSound8K dataset. The goal is to build a system that can contribute to noise pollution monitoring and control.

📂Project Structure

NoisePollutionClassifier/
│
├── data_exploration/
│   └── data_exploration.ipynb                          # Loads dataset, extracts features (MFCC, etc.)
│
├── data_preprocessing & model_training/
│   └── data_preprocessing & model_training.ipynb       # Trains ML model and evaluates accuracy
│
└── README.md                                           # Project documentation

🚀 Features

Loads UrbanSound8K dataset.

Extracts MFCC (Mel-Frequency Cepstral Coefficients) features from audio files.

Trains a Machine Learning classifier (Random Forest / CNN) to classify sounds.

Achieves ~88% accuracy on validation set.

Can be extended into a Smart Noise Pollution Map by integrating with IoT sensors or city-level mapping.

⚙️ Installation & Usage

Clone the repo

git clone https://github.com/56-collab/SmartNoisePollutionMap.git
cd NoisePollutionClassifier


Open in Google Colab

Upload the notebook from each folder.

Or directly run it in Colab after uploading the dataset.

Run step by step

Start with data_exploration/data_exploration.ipynb

Then run data_preprocessing & model_training/data_preprocessing & model_training.ipynb.

📊 Dataset

Dataset: UrbanSound8K

Contains 8,732 labeled urban sound clips of up to 4 seconds each.

Classes include: air_conditioner, car_horn, children_playing, dog_bark, drilling, engine_idling, gun_shot, jackhammer, siren, street_music.

📈 Results

Preprocessing: Extracted MFCC features for each audio file.

Model: Random Forest Classifier

Accuracy: ~88% on test data.

🛠️ Future Work

Add deep learning (CNN/LSTM) models for better accuracy.

Create a real-time noise monitoring system with a microphone.

Integrate with IoT sensors to plot a live Noise Pollution Heatmap for smart cities.

👩‍💻 Author

 Chintagunti Ramyasri

📧 Contact: chintaguntiramyasri05@gmail.com
