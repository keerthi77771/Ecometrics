# 🌍 Matrona: AI-Powered Carbon Footprint Tracker

Matrona is an AI-powered sustainability platform that helps individuals estimate their **carbon footprint** and provides **actionable recommendations** to reduce CO₂ emissions. Using **Google Gemini AI**, it dynamically analyzes user data and offers **personalized sustainability tips** based on the highest emission sources.


## 🚀 Features

✅ **Carbon Footprint Calculator** – Estimate emissions from **transportation, electricity, diet, shopping, and recycling.**  
✅ **AI-Powered Recommendations** – Uses **Gemini AI** to generate sustainability insights.  
✅ **Dynamic Insights** – Identifies the **highest emitting category** and tailors feedback accordingly.  
✅ **Interactive Charts** – Visualize emissions using **pie charts, bar graphs, and comparisons.**  
✅ **User-Friendly UI** – A clean and modern **Streamlit-based** web interface.  


## 📊 How It Works

1. **Enter Lifestyle Data** – Provide details on your **daily habits** (e.g., transport, electricity usage).  
2. **Calculate Emissions** – The system computes **annual and daily CO₂ footprints.**  
3. **Analyze Breakdown** – View a **detailed category-wise breakdown** with interactive charts.  
4. **Get AI Recommendations** – Gemini AI suggests **actionable steps** to cut emissions.  


## 🛠️ Tech Stack

- **Frontend & UI:** Streamlit  
- **Backend & Computation:** Python  
- **AI Model:** Google **Gemini AI** (Generative AI)  
- **Data Visualization:** Matplotlib, NumPy  


## ⚡ Installation & Setup

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/keerthi77771/Ecometrics.git
cd Ecometrics
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up API Key for Gemini AI  
Replace your **Google Gemini API Key** in `backend/ai_recommendations.py`:  
```python
import google.generativeai as genai
GOOGLE_API_KEY = "your_api_key_here"
genai.configure(api_key=GOOGLE_API_KEY)
```

### 4️⃣ Run the Application  
```bash
streamlit run home.py
```

## 📸 Screenshots

🚀 **Homepage** – Introduction & project overview  
📊 **Results Dashboard** – Interactive breakdown & AI insights  
🌱 **Sustainability Tips** – AI-generated emission reduction strategies  


## 🌎 Why Gemini AI?  
Matrona leverages **Google's Gemini AI** for **dynamic and intelligent sustainability insights.** It ensures:  
✔️ **Accurate** & **context-aware** recommendations  
✔️ **Better natural language understanding** than traditional rule-based systems  
✔️ **Scalability** for future enhancements  


## 🤝 Contributing

I welcome **contributions**! Feel free to **fork, modify, and submit pull requests.**  

### 📝 TODO List:
- ✅ Improve AI-generated feedback  
- ✅ Add **region-specific** carbon footprint benchmarks  
- 🔜 Integrate **alternative AI models (e.g., OpenAI, Perplexity)**  
- 🔜 Enhance **UI/UX with more interactive elements**  


## ⭐ Support  
If you like this project, **give it a star ⭐ on GitHub** and share your feedback!  
