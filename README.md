# Soil Type Classification Using CNN  

## Overview  
A CNN-based model classifies soil images into:  
1. **Alluvial Soil**  
2. **Black Soil**  
3. **Laterite Soil**  
4. **Yellow Soil**  

Flask serves as the backend, and React provides the frontend for image upload and classification.  
---

## Model & Dataset  
The model is trained using TensorFlow/Keras and saved as `soil_model.h5`.  

**Note:** Due to file size limitations, the trained model (`soil_model.h5`) is not included in this repository. You can download it from the following link:

🚀 **[Download soil_model.h5](https://drive.google.com/file/d/1IEkKt5iD3hqyycLDZwFHqBxlFn4dnuiK/view?usp=drive_link)**  
Place it in the `backend/` directory before running the Flask server.  
---

## Setup & Installation  

### 🔹 Backend (Flask)  
cd backend
pip install -r requirements.txt
python app.py
The Flask server will run on http://127.0.0.1:5000/.

### 🔹 Frontend (React)  
cd frontend
npm install
cd prediction
npm run dev
The frontend will run on http://localhost:5173/.


