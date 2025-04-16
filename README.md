 # 🤖 Multilingual Mental Health Chatbot 
 
 A smart multilingual chatbot that understands both English and other . It uses language detection,
 real-time translation, and intent classification to respond accurately to user queries through a web interface.

 ---

 ## 👤 Author
 **Saad Shabbir**  
 🔗 [LinkedIn](https://www.linkedin.com/in/saad51)  
 💼 ML Engineer 

 ---

 ## 🗂️ Project Overview
 This project includes:
 - Natural Language Processing (NLP) for intent recognition.
 - Language detection and dynamic translation (English ↔ other ).
 - A trained deep learning model to classify intents.
 - A Flask-based frontend to chat with the bot.

 ---

 ## 🛠️ Setup Instructions

 ### 1️⃣ Create and Activate Virtual Environment
 ```bash
 python -m venv venv
 ```
 On **Linux/macOS**:
 ```bash
 source venv/bin/activate
 ```
 On **Windows**:
 ```bash
 .\venv\Scripts\activate.bat
 ```

 ### 2️⃣ Install Required Libraries
 ```bash
 pip install -r requirements.txt
 ```

 ### 3️⃣ Run the Application
 ```bash
 flask --app app run
 ```

 ---

 ## 🧠 Core Technologies Used
 - **Flask**: For the web app backend
 - **Keras/TensorFlow**: Deep learning model for intent recognition
 - **HuggingFace Transformers**: For other -English translation
 - **Langdetect**: Detect user input language

 ---

 ## 📁 Project Structure
 
 ```
 📦 ChatbotProject/
 ├── app.py                # Flask application and main chatbot logic
 ├── training.py           # Script for training the intent classification model
 ├── intents.json          # File containing sample intents and responses
 ├── model.h5              # Trained neural network model
 ├── texts.pkl             # Pickled tokenized input data
 ├── labels.pkl            # Pickled label data
 ├── requirements.txt      # Project dependencies
 ├── static/               # Static assets (JS, CSS)
 └── templates/index.html  # Frontend UI for the chatbot
 ```

 ---

 ## 💬 Features
 - 🌍 Language auto-detection (English or other )
 - 🔁 Real-time bidirectional translation
 - 🧠 Intent classification using a neural network
 - 🌐 Interactive web interface with Flask

 ---

 ✅ Ready to build, extend, and deploy!
