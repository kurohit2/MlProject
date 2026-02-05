# Student Performance Prediction

An end-to-end Machine Learning project designed to predict student performance based on various demographic and academic parameters. The application is built using Python and Flask, and it is deployed on Render.

## 🚀 Live Demo

The application is live and deployed on Render. Use this link for access:

👉 **[https://mlproject-2-q3hk.onrender.com](https://mlproject-2-q3hk.onrender.com)**

## 📝 Overview

This project demonstrates a complete machine learning pipeline, from data ingestion to deployment. It provides a user-friendly web interface where users can input student details to receive a predicted performance score (typically Math score) based on the trained model.

### Key Features
- **Data Processing**: Handles categorical and numerical features using standard scaling and one-hot encoding.
- **Prediction Pipeline**: Modular code structure separating data ingestion, transformation, and model prediction.
- **Web Interface**: Built with Flask and HTML/CSS for easy interaction.
- **Deployment**: Hosted on Render for public access.

## 🔧 Tech Stack

- **Language**: Python 3.x
- **Web Framework**: Flask
- **Libraries**: Pandas, NumPy, Scikit-learn
- **Deployment**: Render

## 📊 Input Parameters

The model predicts the score based on the following inputs:
- **Gender**: Male/Female
- **Race/Ethnicity**: Group A, B, C, D, E
- **Parental Level of Education**: Bachelor's, Master's, High School, etc.
- **Lunch**: Standard or Free/Reduced
- **Test Preparation Course**: None or Completed
- **Reading Score**: 0-100
- **Writing Score**: 0-100

## 💻 Installation & Usage

To run this project locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd MlProject
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```
   The app will run on `http://0.0.0.0:8080`.

## 👤 Author

**Rohit Kumawat**
- Email: rohitkumawat274@gmail.com