# SmartAgri: AI-Powered Farming Support System 🌾
An innovative AI-powered platform revolutionizing modern agriculture through intelligent automation, data-driven insights, and real-time support for farmers.

# 📖 Overview
The AI-Driven Farming Support System addresses critical challenges in agriculture by integrating advanced AI technologies, including machine learning, computer vision, and natural language processing. Designed to enhance food security and sustainability, it empowers farmers with actionable insights and automation tools.
# 🎯 Problem Statement
Modern agriculture faces significant challenges:

- Unpredictable weather patterns disrupting crop planning
- Declining soil fertility and resource depletion
- Inefficient use of resources (water, fertilizers, labor)
- Limited access to agricultural expertise
- Inadequate livestock and farm security monitoring
- Lack of data-driven decision-making tools

💡 Our Solution
Our system combines multiple AI-driven components to provide a comprehensive farming support platform:
Key Features

- Interactive LLM Chatbot 🤖

  - Real-time farming advice powered by a large language model
  - Answers queries on crop management, pest control, and more
  - Accessible via web and mobile interfaces


- Smart Recommendations 📊

  - Crop Recommender: Suggests optimal crops based on soil, climate, and market trends
  - Fertilizer Recommender: Provides tailored fertilizer plans using soil composition data


- Predictive Analytics 📈

  - Crop Yield Predictor: Forecasts yields using machine learning models
  - Weather Forecasting: Integrates real-time weather APIs for precise planning
  - Disease Detection: Identifies crop diseases early with computer vision


- Monitoring Systems 📹

  - Livestock Monitoring: Tracks animal health and behavior using AI
  - Intruder Detection: Enhances farm security with computer vision-based alerts




## 🚀 Getting Started
Prerequisites

- Backend: Node.js, Python 3.8+, FastAPI, MongoDB
- Frontend: React, Tailwind CSS, Vite
- ML: TensorFlow 2.x, PyTorch 1.x, OpenCV
- Other: Git, npm, pip

Installation

- Clone the Repository
```console

git clone https://github.com/0smanGoni/SmartAgri-AI-Powered-Farming-Support-System.git
cd ai-farming-support
```

- Backend Setup
```console
cd Backend
npm install
cp .env.example .env
```
- Update .env with your API keys and database credentials:
```console
WEATHER_API_KEY=your_key_here
MONGO_URI=your_mongo_uri
```

- Frontend Setup
```console
cd ../Frontend
npm install
```

- ML Models Setup
```console
cd ../ML
pip install -r AnimalDetection/requirements.txt
pip install -r Llama/requirements.txt
```


Running the Application

- Start the Backend
```console
cd Backend
npm start
```

- Launch the Frontend
```console
cd Frontend
npm start

```
- Run ML Services
```console
cd ML/Llama
python app.py
```


Access the application at http://localhost:3000.
# 📱 Usage

- Chatbot: Interact via the web or mobile app to get instant farming advice.
- Recommendations: Upload soil data and receive crop/fertilizer suggestions.
- Dashboard: Monitor real-time analytics, weather forecasts, and security feeds.

🤝 Contributing
We welcome contributions! Follow these steps:

- Fork the repository
- Create a feature branch (git checkout -b feature/YourFeature)
- Commit changes (git commit -m 'Add YourFeature')
- Push to the branch (git push origin feature/YourFeature)
-  Open a pull request


📄 License
This project is licensed under the MIT License. See LICENSE for details.
![License](https://img.shields.io/badge/license-MIT-blue.svg)

🙏 Acknowledgments

Agricultural Research Institute
Weather Data Providers
Open Source Community


