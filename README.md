# 🐍 NoVenom – AI Flask App for Identifying Venomous Animals

NoVenom is a lightweight AI-powered image classification web application built with Flask and Python. Developed as part of the ITD102 Raspberry Pi project at QUT, this app helps users identify whether an animal (such as a snake, spider, or scorpion) is venomous or not by uploading an image.

## 🚀 Features

- 🧠 **AI Classification**: Detects and classifies images using a pre-trained model built with Teachable Machine.
- 🌐 **Web Interface**: Simple user interface built with HTML/CSS and Flask.
- 🍓 **Raspberry Pi Deployment**: Optimized to run on Raspberry Pi for real-world, low-power applications.
- 🐍 **Image Upload & Result Display**: Upload an image and receive an instant classification as "venomous" or "non-venomous".

## 🛠 Tech Stack

`Python`, `Flask`, `HTML`, `CSS`, `Raspberry Pi`, `Teachable Machine`, `Pillow`, `NumPy`

## 📁 File Structure

- `app.py`: Main Flask application file
- `templates/`: Contains HTML files
- `static/`: Stores uploaded images and stylesheets
- `model/`: Contains exported machine learning model files

## 💻 How to Run Locally

```bash
git clone https://github.com/GyeonghwanNoh/Novenom-flask-AI-App.git
cd Novenom-flask-AI-App
pip install flask pillow numpy
python app.py
