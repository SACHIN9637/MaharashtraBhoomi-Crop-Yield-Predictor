# 🌾 MaharashtraBhoomi: Crop Yield Predictor

MaharashtraBhoomi is a web application designed to help farmers predict crop yields based on various parameters like rainfall, area, district, season, and soil quality. The app leverages machine learning models to provide accurate predictions of crop production, aiding farmers in making informed decisions about their agricultural activities.

---

## 🚀 Features

- 📈 **Predict Crop Yield**: Enter crop details like rainfall, area, district, season, and soil quality to predict yield in quintals.
- 🧑‍🌾 **User-Friendly Interface**: Simple and intuitive design tailored for farmers.
- 🗺️ **District Selection**: Choose from various districts of Maharashtra.
- 📱 **Responsive Design**: Mobile-optimized for use in rural areas.
- ⚙️ **Integrated ML Model**: Real-time predictions using Flask API and trained ML models.

---

## 💻 Technologies Used

- 🖼️ **Frontend**: React.js, Bootstrap
- 🧠 **Machine Learning**: XGBoost
- 🔙 **Backend**: Flask (Python)
- 🌐 **Deployment**: Local development server

---

## 🛠️ Installation & Setup

### 1. Clone the Repository


git clone https://github.com/SACHIN9637/MaharashtraBhoomi-Crop-Yield-Predictor.git
cd MaharashtraBhoomi-Crop-Yield-Predictor

###2. Backend Setup (Flask)
cd backend
python -m venv venv
.\venv\Scripts\activate    # On Windows
pip install -r requirements.txt
python app.py


###3.Frontend Setup (React)
cd ../frontend
npm install
npm start


###📁 Project Structure
plaintext
Copy
Edit
MaharashtraBhoomi-Crop-Yield-Predictor/
├── backend/             # Flask API backend
│   ├── app.py
│   ├── model/
│   └── requirements.txt
├── frontend/            # React app
│   ├── src/
│   └── public/
└── README.md


##👤 Maintainer
👨‍💻 Sachin Ganesh Jadhav
🎓 B.Tech, TY Computer Engineering, MIT Academy of Engineering, Pune
🧑‍🏫 Vice President, Mozilla Club MITAOE
📧 Email: sachin.jadhav@mitaoe.ac.in

