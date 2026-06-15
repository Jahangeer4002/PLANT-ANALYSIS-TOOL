# 🌿 Plant Analysis Tool

An AI-powered web application that analyzes plant images and provides detailed information about plant species, health status, care recommendations, characteristics, and interesting facts using Google's Gemini AI.

## 📌 Features

* Upload plant images for analysis
* AI-powered plant identification
* Plant health assessment
* Care and maintenance recommendations
* Detailed plant characteristics
* Interesting facts about plants
* Download analysis reports as PDF
* Simple and user-friendly interface

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js
* Multer (File Upload)
* PDFKit (PDF Generation)

### AI Integration

* Google Gemini 2.5 Flash API

## 📂 Project Structure

```
PLANT-ANALYSIS-TOOL/
│
├── public/
│   └── index.html
│
├── upload/
│
├── reports/
│
├── app.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Jahangeer4002/PLANT-ANALYSIS-TOOL.git
cd PLANT-ANALYSIS-TOOL
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_gemini_api_key
PORT=5000
```

### Run the Application

```bash
npm start
```

or

```bash
node app.js
```

Open:

```
http://localhost:5000
```

## 📖 How It Works

1. Upload a plant image.
2. The image is sent to the backend.
3. Gemini AI analyzes the plant.
4. Detailed plant information is generated.
5. Users can download the analysis as a PDF report.

## 🎯 Use Cases

* Plant Identification
* Gardening Assistance
* Agriculture Learning
* Botanical Education
* Plant Health Monitoring

## 🔒 Environment Variables

| Variable       | Description           |
| -------------- | --------------------- |
| GEMINI_API_KEY | Google Gemini API Key |
| PORT           | Server Port           |

## 🌐 Deployment

This application is deployed on Render:

https://plant-analysis-tool-8xer.onrender.com

## 👨‍💻 Author

**Md Jahangeer**

* GitHub: https://github.com/Jahangeer4002
* LinkedIn: https://www.linkedin.com/in/md-jahangeer-11b69328b/

## 📜 License

This project is developed for educational and portfolio purposes.
