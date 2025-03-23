# Fitness_Tracking_application
---
# Personal Fitness Tracker

## 📌 Overview
This **Personal Fitness Tracker** is a Python-based health tracking application built using **Streamlit**. It allows users to log their daily health metrics such as BMI, calories burned, workout duration, and sleep hours while providing personalized fitness and diet recommendations.
---
## 🚀 Features
- **BMI Calculator**: Calculates BMI based on height and weight.
- **Calories Burned Estimator**: Estimates calories burned based on daily activity.
- **Workout & Sleep Recommendations**: Provides tailored fitness suggestions.
- **Diet Plan Suggestions**: Recommends an appropriate diet based on BMI.
- **Water Intake Tracker**: Logs daily water consumption.
- **Custom Background & UI Enhancements**: Stylish background with easy-to-use UI.
---
## 🛠️ Installation

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-username/Personal-Fitness-Tracker.git
cd Personal-Fitness-Tracker
```

### 2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 3️⃣ **Run the Application**
```bash
streamlit run fitness_app.py
```
---
### 📂 Files in the Repository
#### **fitness_app.py** → Main application script.
#### **dataset-2.csv** → Sample dataset for tracking user fitness data.
#### **diet_dataset_2.csv** → Dataset for diet recommendations.
#### **fitness_health.webp** → Background image.
---
### 🔥 Usage
#### Enter your age, height, weight, daily steps, workout minutes, and sleep hours.
#### Click on 'Get Recommendation'.
#### View your BMI, calories burned, workout advice, and diet plan.
#### Use the insights to improve your health & fitness!
---
### 🎨 UI & Background Customization
#### The application includes a custom background using a local image converted to Base64. If you want to change the background:
#### Replace fitness_health.webp with your desired image.
#### Update the image_path in fitness_app.py to point to the new file.
#### Restart the application.
---
### ⚠️ Troubleshooting
#### **OSError (Invalid File Path):** Ensure the image path uses the correct format **(r"path/to/image" or D:\\path\\to\\image)**.
#### Missing Dataset Files: Ensure dataset-2.csv and diet_dataset_2.csv exist in the project folder.
#### Streamlit Not Found: If you get an error, install it with:
```bash
pip install streamlit
```
---
### 📜 License
#### This project is open-source and available under the MIT License.
---
### 📌 Project-Demo
🟢 **Live Demo**: [Fitness App](https://fitnessapppy-cdpeamwjv69vzscwayjuva.streamlit.app/)
