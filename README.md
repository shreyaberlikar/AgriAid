# 🌱 AgriAid – AI Crop Disease Diagnosis System

AgriAid is an AI-powered crop disease diagnosis and medicine recommendation system built using **Groq LLM**, **Tavily Search API**, and **Gradio**. Farmers can enter crop symptoms, and the system intelligently predicts the disease, retrieves real-time medicine recommendations with purchase links, and provides prevention tips through an interactive web interface.

---

## 🚀 Features

- 🌾 Enter crop name and symptoms
- 🤖 AI-powered disease prediction using Groq LLM
- 🔍 Real-time medicine recommendations using Tavily Search API
- 💊 Suggests top medicines for the detected disease
- 🔗 Provides medicine purchase links
- 🛡️ Offers prevention and crop care tips
- 🎨 Simple and interactive Gradio UI

---

## 🛠️ Tech Stack

- Python
- Groq (Llama 3.1 8B Instant)
- Tavily Search API
- Gradio
- Google Colab

---

## 📂 Project Workflow

```text
Farmer Input
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
(Get Medicines & Links)
      │
      ▼
Create Context
      │
      ▼
Groq LLM
(Generate Final Report)
      │
      ▼
Gradio UI
(Display Results)
```

---

## 📸 Output

The application generates a structured report including:

- 🌱 Crop Name
- 🦠 Predicted Disease
- 📝 Reason for Prediction
- 💊 Recommended Medicines
- 🔗 Medicine Purchase Links
- 🛡️ Prevention Tips

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/AgriAid.git
cd AgriAid
```

Install dependencies:

```bash
pip install gradio groq tavily-python
```

Run the application:

```bash
python app.py
```

---

## 🎯 Future Enhancements

- 📷 Crop image-based disease detection
- 🌍 Multilingual support
- 🎤 Voice-based symptom input
- ☁️ Weather API integration
- 📊 Disease history dashboard
- 📱 Mobile application support

---

## 🤝 Contributing

Contributions, suggestions, and feature requests are welcome. Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

### ⭐ If you found this project helpful, consider giving it a Star on GitHub!
