
# 🏆 Sports Personality Classifier

This is a Data Science and Machine Learning project that classifies images of famous sports personalities using a custom-trained model. The classification is limited to the following five athletes:

- 🎾 Maria Sharapova  
- 🎾 Serena Williams  
- 🏏 Virat Kohli  
- 🎾 Roger Federer  
- ⚽ Lionel Messi  

---

## 📁 Project Structure

```bash
├── UI/                       # Frontend code (HTML/CSS/JS)
├── server/                  # Python Flask server backend
├── model/                   # Jupyter notebooks for model building & training
├── google_image_scrapping/  # Scripts to scrape training images from Google
├── images_dataset/          # Collected dataset of images for training
```
---

## 🚀 Features
- Image classification of 5 global sports icons.
- End-to-end pipeline: Image scraping → Preprocessing → Model training → Web-based prediction.
- Intuitive and responsive UI.
- Lightweight Flask backend for model inference.

---

##  Technologies & Tools Used

### Programming & Libraries

- **Python** for scripting and backend
- **NumPy, OpenCV** for image preprocessing and data cleaning
- **Matplotlib, Seaborn** for visualization
- **scikit-learn** for building the classification model

### 🛠 IDEs & Tools
- **Jupyter Notebook** for model development  
- **Visual Studio Code** and **PyCharm** for project development  
- **Flask** for serving the model via HTTP

### 🌐 Frontend
- **HTML/CSS/JavaScript** for user interface

---

## 🖼️ Dataset

The dataset is curated using Google Image Scraping scripts and manually organized under `images_dataset/`. The data is preprocessed using OpenCV and then used to train a classification model.

---

## 🧪 Model Training

Model training scripts and Jupyter Notebooks can be found in the `model/` folder. The process includes:
1. Loading and cleaning images
2. Feature extraction
3. Training a classification model using `scikit-learn`

---

## 🌍 Web Interface

The UI built with HTML/CSS/JS allows users to upload an image and get real-time predictions. It communicates with the Flask server which loads the model and returns the classification result.

---

## 🏁 How to Run the Project

1. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Flask server**
   ```bash
   cd server
   python app.py
   ```
3. **Open the UI**
   Open UI/index.html in your browser (ensure it can communicate with the local Flask server).

---

![](ui_snapshot.jpg)

---
