# Chatbot with Rule-Based and Deep Learning Models

## 🚀 Introduction
This project is a hybrid chatbot that combines **rule-based responses** and a **deep learning model (GPT-2)** to provide intelligent and dynamic conversations. The chatbot is implemented using **Python, Streamlit, and Hugging Face Transformers**.

## 📂 Project Structure
```
📁 chatbot_project
│── 📁 Chatbot_Model/             # Trained GPT-2 model (Saved after training)
│── 📜 intents.json               # JSON file containing rule-based chatbot responses
│── 📜 chatbot.ipynb              # Jupyter Notebook for training GPT-2 chatbot
│── 📜 app.py                     # Streamlit application for chatbot interface
│── 📜 README.md                  # Project documentation
│── 📜 requirements.txt            # List of dependencies
```

## 🛠 Installation & Setup
### Step 1: Clone the Repository
```sh
git clone https://github.com/sakuna47/chatbot_project.git
cd chatbot_project
```

### Step 2: Create a Virtual Environment (Optional)
```sh
python -m venv chatbot_env
source chatbot_env/bin/activate   # On macOS/Linux
chatbot_env\Scripts\activate      # On Windows
```

### Step 3: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 4: Train the Chatbot (Optional)
If you haven't trained the GPT-2 model yet, run the Jupyter Notebook `chatbot.ipynb` to train and save the model.

### Step 5: Run the Streamlit App
```sh
streamlit run app.py
```

## 🎯 Features
✅ **Rule-Based Chatbot** – Uses predefined responses from `intents.json`.
✅ **Deep Learning Chatbot** – Uses GPT-2 to generate dynamic responses.
✅ **Interactive UI** – Built using Streamlit for an easy-to-use chat interface.
✅ **Chat History** – Stores and displays previous messages.

## 📌 Usage
1. Open the Streamlit app.
2. Select **Rule-Based** or **Deep Learning** chatbot from the sidebar.
3. Type a message and interact with the chatbot.

## 🔥 Technologies Used
- Python 🐍
- Streamlit 🎨
- Hugging Face Transformers 🤗
- GPT-2 Model 🧠
- JSON (for intents data)
- NLTK (Natural Language Processing)

## 📝 Future Improvements
🔹 Improve GPT-2 responses with fine-tuning.
🔹 Add more predefined responses in `intents.json`.
🔹 Deploy chatbot using Streamlit Cloud or Hugging Face Spaces.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

## 📜 License
This project is open-source under the **MIT License**.

## 🌟 Acknowledgments
Special thanks to **Hugging Face** for providing powerful NLP models and **Streamlit** for an easy web UI framework.

---
### 🎯 Stay Connected
💬 Need help? Reach out to me via **GitHub Issues** or open a discussion thread!

