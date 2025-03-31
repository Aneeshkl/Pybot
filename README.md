
# 🤖 PyBot - AI Chatbot  
_A Flask-based AI chatbot with a modern UI and AI-powered responses._  

## 📚 Overview  
**PyBot** is a chatbot built using **Flask** and **DialoGPT**, providing a real-time chat interface with a sleek and modern UI. The chatbot can process user messages and generate AI-based responses.  

## 🚀 Features  

### 🔹 Chatbot Capabilities  
✅ AI-powered responses using **DialoGPT**  
✅ User-friendly **dark-themed UI**  
✅ **Real-time chat interface**  
✅ Customizable chatbot theme  

### 🔹 Tech Stack  
🔹 **Backend:** Flask (Python)  
🔹 **Frontend:** HTML, CSS (with custom styles)  
🔹 **AI Model:** `DialoGPT` (by Microsoft)  
🔹 **Tools Used:** PyCharm  

## 📂 Project Structure  
```
PyBot/
│── static/
│   ├── style.css           # Custom CSS for UI styling
│   ├── AI Image.jpg        # Background image for chatbot
│── templates/
│   ├── chat.html           # Chat interface frontend
│── app.py                  # Main Flask application
│── requirements.txt        # Required dependencies
│── README.md               # Documentation
```  

## 🛠️ Setup & Installation  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/PyBot.git
cd PyBot
```  

### 2️⃣ Create a Virtual Environment  
```sh
python -m venv venv
```
Activate the virtual environment:  
- **Windows:**  
  ```sh
  venv\Scripts\activate
  ```
- **Mac/Linux:**  
  ```sh
  source venv/bin/activate
  ```  

### 3️⃣ Install Required Libraries  
```sh
pip install -r requirements.txt
```  

### 4️⃣ Run the Chatbot  
Start the Flask application:  
```sh
python app.py
```
Then, open a browser and visit:  
```
http://127.0.0.1:5000
```

## 📜 Required Libraries  
Make sure you have the following dependencies installed (**already in `requirements.txt`**):  
```txt
Flask
torch
transformers
flask_ngrok
```

## 🖼️ Screenshots   
![📌 **Chat Interface**](PowerBIDashboard.png)

## 📊 How It Works  
1️⃣ **User enters a message** in the chat input.  
2️⃣ **PyBot processes the input** using `DialoGPT`.  
3️⃣ **AI generates a response**, displayed in the chat window.  

## 📩 Contact & Contributions  
📩 Email: aneabidevraji@gmail.com  
🔗 LinkedIn: (https://www.linkedin.com/in/aneesh-s-nkl)  

Feel free to **fork the repository** and enhance PyBot with **more AI models, better UI animations, and WebSocket for real-time chat!**  

---

💡 **Enjoy using PyBot! 🚀**
