---

# 🧠 Summarizer Extension

A Chrome extension that summarizes the content of any article or webpage using AI! This tool helps users quickly understand lengthy content without reading the entire page.


## 🚀 Features

* 📝 Summarizes web articles instantly
* 🧠 Uses Gemini API for smart, accurate summarization
* 🧩 Simple, lightweight Chrome extension
* ⚡ One-click summary generation
* 🎯 Useful for students, professionals, and researchers

---

## 🛠️ Tech Stack

* **JavaScript**
* **HTML & CSS**
* **Manifest v3 (Chrome Extensions)**
* **Gemini API** (Google AI)

---

## 📦 Installation

1. Clone this repo:

   ```bash
   git clone https://github.com/Abhay-0103/Summarizer-Extension.git
   ```

2. Open Chrome and go to:

   ```
   chrome://extensions/
   ```

3. Enable **Developer Mode** (top right)

4. Click **Load unpacked** and select the cloned folder

5. The extension will now appear in your Chrome extensions list!

---

## 🧪 Usage

1. Navigate to any article or webpage
2. Click the extension icon (🧠)
3. Hit the **Summarize** button
4. Read the generated summary instantly!

---

## 🔐 Setup Gemini API Key

To make the summarizer work:

1. Get your Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Open `config.js` in the extension folder
3. Replace `YOUR_API_KEY_HERE` with your actual key:

   ```js
   const GEMINI_API_KEY = 'YOUR_API_KEY_HERE';
   ```

---

## 📁 Project Structure

```
Summarizer-Extension/
├── popup.html
├── popup.js
├── config.js
├── manifest.json
├── style.css
└── README.md
```

---

## 💡 Future Improvements

* Add support for summarizing YouTube video transcripts
* Improve UI/UX with better animations and theme
* Add history and export options for summaries

---

## 🤝 Contribution

Pull requests and suggestions are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

---

---

## 🌟 Show Your Support

Give a ⭐ if you found this helpful or want to support the project!

---
