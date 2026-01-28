# 🍏 SmartEats - Intelligent Food Choice Assistant

## 📋 Objective

SmartEats empowers users to make informed, healthier food choices by instantly analyzing product barcodes and revealing comprehensive nutritional insights. Simply scan, see, and decide smarter.

## ✨ Key Features

- **📸 Instant Barcode Scanning**: Capture product barcodes using your device's camera
- **📊 Comprehensive Nutrition Analysis**: View detailed nutritional information including calories, sugars, fats, proteins, fiber, and more
- **💯 Healthiness Score**: Get an objective 0-100 health rating based on nutritional content and ingredient quality
- **🌐 Real-Time Data**: Powered by the Open Food Facts database with information on millions of products worldwide
- **📱 User-Friendly Interface**: Clean, intuitive design for seamless user experience

## 🎯 How It Works

1. **Scan**: Use your camera to capture a product's barcode
2. **Analyze**: SmartEats retrieves nutritional data and evaluates ingredient quality
3. **Decide**: Review the healthiness score and detailed nutrition facts to make informed choices

## 🛠️ Technology Stack

**Frontend:**
- HTML5, CSS3, JavaScript
- Bootstrap 4
- Feather Icons

**Backend:**
- Python Flask
- Flask-RESTful API
- OpenCV & PIL for image processing
- pyzbar (Python wrapper for ZBar barcode decoder)

**Data Source:**
- Open Food Facts API

## 🚀 Getting Started

### Backend Setup
```bash
cd "Back End"
pip install flask flask-restful flask-cors pillow pyzbar opencv-python requests
python api.py
```

### Frontend Setup
```bash
cd "Front End"
# Serve using any HTTP server
python -m http.server 8000
# Or use the provided local server
python "../local http server.py"
```

Access the application at `http://localhost:8000`

## 📈 Health Score Algorithm

SmartEats calculates healthiness scores based on:
- **Nutritional Content (70 points max)**: Fiber, protein, vitamins, minerals vs. saturated fats, trans fats, sodium, and calories
- **Ingredient Quality (30 points max)**: Whole food content, organic ingredients, absence of artificial additives and harmful ingredients

**Score Categories:**
- 90-100: Excellent
- 50-89: Average
- 0-49: Poor

## 🤝 Contributing

Contributions are welcome! This project aims to promote healthier eating habits through technology.

## 📄 License

This project was developed as part of the NeoDev initiative to create impactful health-focused applications.

---

**Made with 💚 for healthier living**
