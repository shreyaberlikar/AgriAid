# 🌱 AgriAid – AI-Powered Crop Disease Diagnosis System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Groq-LLM-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tavily-Search_API-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Gradio-UI-red?style=for-the-badge"/>
</p>

## 🌾 Overview

**AgriAid** is an AI-powered crop disease diagnosis system designed to help farmers identify crop diseases from symptoms and receive real-time treatment recommendations.

The application uses **Groq LLM** to understand crop symptoms, **Tavily Search API** to retrieve the latest medicine information from the web, and **Gradio** to provide an interactive user interface.

---

## ✨ Features

✅ AI-based crop disease prediction

✅ Understands natural language symptoms

✅ Real-time medicine recommendations

✅ Medicine purchase links

✅ Prevention and crop care tips

✅ Beautiful Gradio web interface

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend |
| Groq Llama 3.1 | Disease Prediction & Report Generation |
| Tavily Search API | Real-time Medicine Search |
| Gradio | Interactive Web Interface |

---

# 🚀 Workflow

```text
Farmer
    │
    ▼
Enter Crop Name & Symptoms
    │
    ▼
Groq LLM
(Predict Disease)
    │
    ▼
Tavily Search API
(Search Medicines & Treatment)
    │
    ▼
Collect Search Results
    │
    ▼
Groq LLM
(Generate Final Report)
    │
    ▼
Gradio UI
(Display Diagnosis)
```

---

# 📋 Output

The system generates:

🌱 Crop Name

🦠 Predicted Disease

📝 Diagnosis Reason

💊 Top Recommended Medicines

🔗 Medicine Purchase Links

🛡 Prevention Tips

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/your-username/AgriAid.git
```

Move into the project

```bash
cd AgriAid
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

---

# 🎯 How It Works

### Step 1
The farmer enters the crop name and symptoms.

⬇️

### Step 2
Groq LLM analyzes the symptoms and predicts the most likely disease.

⬇️

### Step 3
Tavily searches the web for:

- Medicines
- Treatments
- Purchase Links

⬇️

### Step 4
The retrieved information is combined into a context.

⬇️

### Step 5
Groq LLM generates a structured diagnosis report.

⬇️

### Step 6
The report is displayed in the Gradio interface.

---

# 📸 Example Input

### Crop

```text
Tomato
```

### Symptoms

```text
Yellow spots on leaves

Brown circular patches

Leaves are curling

Plant growth has slowed down
```

---

# 📸 Example Output

```text
🌱 Crop : Tomato

🦠 Disease :
Early Blight

📝 Reason :
The symptoms closely match Early Blight caused by
Alternaria solani.

💊 Recommended Medicines

• Mancozeb
• Chlorothalonil
• Copper Oxychloride

🔗 Purchase Links

https://....

https://....

🛡 Prevention Tips

• Remove infected leaves
• Avoid overhead irrigation
• Practice crop rotation
```

---

# 🌍 Future Improvements

- 📷 Image-based disease detection

- 🌦 Weather API integration

- 🗣 Voice-based symptom input

- 🌐 Multi-language support

- 📱 Android Application

- 📊 Farmer Dashboard

---

# 🤝 Contributing

Contributions, ideas, and feature requests are welcome.

Fork the repository and create a Pull Request.

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

It motivates me to build more AI-powered projects!

---

<p align="center">

Made with ❤️ using Python, Groq LLM, Tavily Search API & Gradio

</p>
