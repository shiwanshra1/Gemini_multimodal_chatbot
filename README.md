
# 🤖 Multimodal Chatbot Using Gemini Flash ⚡️

Engage with Google's cutting-edge **Gemini Flash** model using both **text and image inputs** to experience intelligent, lightning-fast, and highly detailed responses. Whether you're asking questions, analyzing visuals, or combining both — this chatbot delivers rich, contextual answers within seconds.

![Gemini Flash Banner](https://img.shields.io/badge/Powered%20by-Google%20Gemini%201.5%20Flash-blue)

## 🔥 Features

- 💬 Natural, conversational interface using Streamlit
- 🧠 Powered by **Gemini 1.5 Flash** – fast and multimodal
- 📸 Upload `.jpg`, `.jpeg`, or `.png` images to enhance prompts
- 🧾 Maintains chat history during session
- 🖼️ Displays image previews inside the UI
- ⚙️ Easy setup with Google Generative AI API key

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/shiwanshra1/Gemini_multimodal_chatbot.git
cd Gemini_multimodal_chatbot
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install streamlit google-generativeai Pillow
```

### 3. Run the App

```bash
streamlit run app.py
```

### 4. Enter Your API Key

Get your key from [Google AI Studio](https://makersuite.google.com/app) and paste it in the app when prompted.

---

## 🧠 How It Works

This app sends your prompt (and optional image) to the **Gemini 1.5 Flash** model using the official `google-generativeai` Python SDK and displays the generated response right inside the Streamlit interface.

### Example Use Cases

- 📸 Ask questions about images (e.g., “What’s happening in this photo?”)
- 💬 Combine image with text for richer interaction
- 💡 Analyze content, ask about design, get creative writing help

---

## 📁 Project Structure

```
.
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 🔐 API Key Setup

1. Go to [https://makersuite.google.com/app](https://makersuite.google.com/app)
2. Sign in with your Google account
3. Generate an API key
4. Paste it into the input field in the app

---

## 📎 Links

- 📂 GitHub Repo: [Gemini Multimodal Chatbot](https://github.com/shiwanshra1/Gemini_multimodal_chatbot.git)

---

## 📌 Notes

- Internet is required to call the Gemini model
- Input images should be clear and under 5MB for best results
- Session data resets when you refresh the app

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
