#🌴 Sa’af – Intelligent Palm Tree Health Monitoring Platform  

## 📌 Introduction  
Palm trees are a vital agricultural and economic resource in Saudi Arabia and the Arab world. However, they face challenges such as **Red Palm Weevil infestations, water stress, and nutrient deficiencies**. Traditional inspection methods are often **time-consuming, costly, and limited in scale**, making early detection difficult.  

**Sa’af** is a smart platform that leverages **satellite imagery and Artificial Intelligence (AI)** to monitor palm tree health and provide early detection of potential risks. The system supports farmers and agricultural organizations by reducing losses and improving farm management.  

## 🛠️ Technologies Used  
- **Frontend:** Flutter SDK  
- **Backend:** Python (Flask)  
- **APIs & Data Sources:** Google Earth Engine, Sentinel Hub API, Sentinel-2 & Landsat-8 satellite imagery  
- **AI & Data Science:** Machine Learning, Deep Learning (CNN), Vegetation Indices (NDVI, NDMI, NDRE), Time-Series Analysis  
- **Database:** MySQL  
- **Visualization:** Interactive maps, dashboards, and reports  

## 🚀 Project Features  
- User registration & login (Farmers & Admin)  
- Add and manage farms with GPS coordinates  
- Interactive map to view farm locations and palm health status  
- Automated analysis of satellite imagery (NDVI, NDMI, NDRE)  
- AI-based classification of palm tree health (Healthy, Infected, Water Stress, Nutrient Deficiency)  
- Early warning and notification system  
- Admin dashboard for monitoring farms and managing users  
- Report generation (PDF/Excel)  


## ⚙️ Launching Instructions  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/YourOrg/2025_GP_GroupNumber.git
   cd 2025_GP_GroupNumber
   ```

2. **Backend Setup (Flask):**  
   ```bash
   cd backend
   pip install -r requirements.txt
   python app.py
   ```

3. **Frontend Setup (Flutter):**  
   ```bash
   cd frontend
   flutter pub get
   flutter run
   ```


4. **Database Setup:**
- Import the provided SQL file into MySQL
- Update the database credentials in config.php or .env
