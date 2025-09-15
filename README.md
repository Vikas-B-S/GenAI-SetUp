# 🚀 Generative AI Text Generation App (Gemini + Streamlit)

A simple **Generative AI application** built with **Google’s Gemini API** and **Streamlit**.  
This app takes user prompts and generates text responses using the **Gemini 2.5 Flash Lite** model.  

---

## 📂 Project Structure
```
├── app.py              # Streamlit app with Gemini integration
├── gemini.ipynb        # Notebook for testing Gemini model
├── requirements.txt    # Dependencies
```

---

## ⚡ Features
-  Integrated **Gemini 2.5 Flash Lite** model via `google.generativeai`  
-  **Streamlit UI** for interactive text generation  
-  Secure API key handling using environment variables  
-  Lightweight and extensible starter project for **GenAI apps**  

---

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vikas-B-S/GenAI-SetUp.git
   cd GenAI-SetUp
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set your Google API Key**
   ```bash
   export GOOGLE_API_KEY="AIzaSyDHOJnqZppQq_4-3C_SCYdob4yxnZdlsRM"   # Linux/Mac
   setx GOOGLE_API_KEY "AIzaSyDHOJnqZppQq_4-3C_SCYdob4yxnZdlsRM"     # Windows
   ```

---

## ▶️ Run the App
```bash
streamlit run app.py
```

---

## 💡 Future Improvements
- Add **text summarization & chatbot features**  
- Extend to **multimodal input (text + image)**  
- Deploy on **Streamlit Cloud / Hugging Face Spaces**  

---

## 🧑‍💻 Tech Stack
- Python  
- Streamlit  
- Google Gemini API (`google.generativeai`)  

---

## App Link
- Click here : https://genai-setup-vikas-b-s.streamlit.app/