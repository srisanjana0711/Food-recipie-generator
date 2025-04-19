# 🍽️ Talk to Taste  
**AI-Generated Recipes Based on How You Feel** 🤖💬

---

## 1️⃣ Project Overview

This project is a **mood-based food recipe recommendation system** that uses artificial intelligence to generate recipes tailored to the user's emotional state. By analyzing natural language input, the system detects sentiment and responds with a custom recipe suggestion using advanced language models.

Built with:
- 🔍 DistilBERT for sentiment classification  
- 🍳 Falcon-7B-Instruct via Hugging Face for recipe generation  
- 🖼️ Gradio for an interactive front-end

---

## ✨ Features

- 🧠 Mood-to-meal personalization using NLP  
- ⏱️ Real-time sentiment analysis  
- 📋 AI-generated recipes (ingredients + cooking steps)  
- 🗂️ Custom food category mapping  
- 🌐 Clean Gradio web interface  

---

## ⚙️ Getting Started

### 🧰 Prerequisites

- 🐍 Python 3.8+  
- 🔑 Hugging Face account + API key  
- 📦 Install dependencies via `pip`  

### 💻 Installation

```bash
git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName
pip install -r requirements.txt
```

### 🔐 API Configuration

In your code, replace the placeholder with your actual Hugging Face API key:

```python
API_KEY = "****YOUR_HUGGING_FACE_API_KEY****"
```

---

## 🚀 Usage

Run the app locally using:

```bash
python app.py
```

🗨️ Enter a mood-based sentence (e.g., *"I’m feeling stressed and exhausted"*)  
🍲 Receive a personalized, AI-generated recipe suggestion

---

## 📊 Example Output

| 💬 **User Mood Input**                          | 🧠 **Sentiment** | 🍽️ **Category**     | 🧾 **Suggested Recipe**             |
|------------------------------------------------|------------------|----------------------|-------------------------------------|
| I’m feeling low and tired                      | Negative         | Comfort food         | Creamy Mushroom Soup                |
| I feel happy and want something refreshing     | Positive         | Fruit-based          | Berry Yogurt Smoothie Bowl          |

---

## 🖼️ Output Screenshots

Some screenshots from the application in action:

![Screenshot 2025-04-05 192156](https://github.com/user-attachments/assets/61d47acd-10c6-48d7-8926-69e4bd5ff00d)


![Screenshot 2025-04-05 185520](https://github.com/user-attachments/assets/f55f1814-99cc-456f-9abd-adf5fbcf6cd3)

---

## 📁 Project Structure

```
project/
├── food.ipynb
├── README.md
```

---

## ⚠️ Notes

- 🔐 Keep your Hugging Face API key secure and avoid sharing it publicly.  
- 🕒 Falcon-7B may take a few seconds to generate responses depending on server load.

---

## 📜 License

This project is intended for educational and research use only. 📘

---

### **🧑‍💻 Author**
👤 **Srisanjana Karunamoorthy**  
🔗 GitHub: [srisanjana0711](https://github.com/srisanjana0711)  

---

