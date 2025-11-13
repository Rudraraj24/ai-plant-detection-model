# 🌿 PlantDetect AI — Intelligent Plant Disease Detection

**PlantDetect AI** is an AI-powered web application that detects plant leaf diseases and provides detailed insights — including causes, prevention methods, and supplement recommendations.  
It also includes interactive tools for exploring crop suitability by region and a marketplace for fertilizers and pesticides.

---

## 🚀 Features

- 🧠 **CNN-Based Detection:** Deep learning model achieving ~98% accuracy on common plant diseases.  
- 💡 **Comprehensive Insights:** Displays disease name, cause, prevention tips, and supplement suggestions.  
- 🛒 **Integrated Store:** Explore and purchase fertilizers & pesticides directly from the app.  
- 🗺️ **Interactive Crop Map:** Visualize which crops grow best in various regions.  
- 🌱 **Plant Environment Guide:** Interactive indoor and outdoor plant grids for gardeners.

---

## 🛠️ Tech Stack

- **Languages & Libraries:** Python, PyTorch, NumPy, Pandas  
- **Framework:** Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **Other Tools:** Embedded product integrations and map-based exploration

---

## 📁 Project Structure
Plant_Disease_Detection/
├── static/uploads/ # Uploaded leaf images
├── templates/ # HTML templates for frontend
│ ├── contact-us.html # Contact form page
│ ├── home.html # Homepage with plant grids
│ ├── index.html # Landing page
│ ├── indoor.html # Indoor plant suggestions
│ ├── outdoor.html # Outdoor plant suggestions
│ ├── map.html # Crop suitability map
│ ├── market.html # Fertilizer/pesticide cart
│ ├── submit.html # Prediction results page
├── Model/ # Trained CNN model weights
├── CNN.py # Model architecture and prediction logic
├── app.py # Flask backend and routing
├── requirements.txt # Project dependencies
├── .gitignore # Git ignore configuration
└── README.md # Project documentation


---

## 🧩 How It Works

1. Upload a leaf image using the web interface.  
2. The CNN model analyzes and classifies the disease.  
3. The app returns results including:
   - Detected disease name  
   - Causes and prevention tips  
   - Recommended supplements and pesticides  
4. Optionally explore related products or maps.

---
📸 Example Output

Input: Uploaded plant leaf image

Output:

Predicted disease name

Cause and prevention tips

Recommended fertilizers/pesticides

Environmental plant guide

👨‍💻 Author

Rudraraj Radhwani
B.Tech CSE (AI & ML), K.R. Mangalam University
GitHub: @Rudraraj24


