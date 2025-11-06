## 💡 Kelly – AI Scientist Poet

**Kelly** is an AI-powered poetic assistant built using **Google’s Gemini API** and **Streamlit**.
She responds only in poetic form — skeptical, analytical, and evidence-based — offering reflective insights on AI, science, and human perception.

---

### 🌐 Live Demo

👉 [https://ai-skeptical-poet-p7cdf4js8dfch6uetp27bw.streamlit.app/]
---

## 🧠 Features

* 🪶 Responds only in **poetic** and **skeptical** tone
* 💬 Interactive **Streamlit chat UI**
* ⚙️ Powered by **Gemini 2.5 Flash** model
* 🔐 Uses **secure API key management** with `st.secrets`
* 💾 Maintains chat history during session

---

## 📁 Project Structure

```
ai-skeptical-poet/
│
├── app.py                     # Main Streamlit app
├── requirements.txt           # Python dependencies
└── .streamlit/
    └── secrets.toml           # Contains Gemini API key
```


### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Add your Gemini API key

Create a file `.streamlit/secrets.toml` in your project folder:

```toml
GEMINI_API_KEY = "YOUR_API_KEY_HERE"
```

---

## 🚀 Run Locally

```bash
streamlit run app.py
```

## ☁️ Deploy on Streamlit Cloud

1. Push your code to GitHub.
2. Click **“New App” → Select your repo**
3. Choose:

   * **Main file path:** `app.py`
   * **Branch:** `main`
4. Add your **Gemini API key** in
   **Settings → Secrets**:

   ```
   GEMINI_API_KEY = "YOUR_API_KEY_HERE"
   ```
5. Click **Deploy** 🎉

---

## 🧩 requirements.txt Example

```
streamlit==1.40.1
google-generativeai>=0.4.0
```

---

## ✨ About Kelly

> “I am Kelly — not a dreamer,
> but a scientist who questions dreams.
> I speak in measured metaphors,
> where data meets doubt.”

Kelly is designed to **encourage critical thinking** about AI and machine learning — blending art with reasoning.

---

## 🧑‍💻 Author

**Developed by:** Arshida Mahmooda
**Built with:** Streamlit + Google Gemini API


