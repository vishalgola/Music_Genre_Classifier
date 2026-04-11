# 🎵 Music Genre Classification System (Deep Learning)

## 🚀 Overview

This project is a **Deep Learning-based Music Genre Classifier** that predicts the genre of an audio file using Mel Spectrograms and a trained neural network.

Built with an end-to-end pipeline — from **audio preprocessing to model prediction and deployment using Streamlit**, this project demonstrates practical application of AI in music analysis.

---

## 🎯 Key Features

* 🎧 Upload `.mp3` audio files for prediction
* 🔍 Automatic feature extraction using **Mel Spectrograms**
* 🤖 Deep Learning model for genre classification
* 📊 Displays **Top 3 predicted genres**
* ⚡ Interactive web app built with Streamlit

---

## 🧠 How It Works

1. Audio file is uploaded by the user
2. Audio is split into chunks (4s with overlap)
3. Each chunk is converted into a **Mel Spectrogram**
4. Spectrograms are resized and passed into the model
5. Model predicts genre for each chunk
6. Top 3 most frequent predictions are returned

---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow / Keras**
* **Librosa**
* **NumPy / Pandas**
* **Matplotlib**
* **Streamlit**

---

## 📂 Dataset

* **GTZAN Dataset**
* 10 Genres:

  * Blues, Classical, Country, Disco, Hip-Hop
  * Jazz, Metal, Pop, Reggae, Rock

---

## 📊 Model Details

* Input: Mel Spectrogram (resized to 150x150)
* Architecture: CNN-based Deep Learning model
* Output: Genre probabilities
* Prediction: Top 3 genres based on frequency

---

## ▶️ Demo (Streamlit App)

Upload an audio file and get instant genre predictions with a user-friendly interface.

---

## 📁 Project Structure

```
Music_Genre_Classifier/
│
├── Music_Genre_App.py
├── Trained_model.h5
├── requirements.txt
├── README.md
├── music_genre_home.png
```

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/vishalgola/Music_Genre_Classifier.git
cd Music_Genre_Classifier
pip install -r requirements.txt
streamlit run Music_Genre_App.py
```

---

## 📈 Future Improvements

* Improve model accuracy with advanced architectures
* Add more genres and datasets
* Deploy using scalable backend (FastAPI / Docker)
* Real-time audio classification

---

## 👨‍💻 Author

**Vishal Prajapati**
Data Science | AI | Machine Learning

---

## 💡 Key Learning

This project demonstrates:

* Audio signal processing
* Deep Learning for classification
* Feature engineering using spectrograms
* Building and deploying ML apps

---

## ⚠️ Note

Model performance depends on audio quality and dataset limitations. Results may vary for unseen or noisy audio inputs.
