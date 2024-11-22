
---

# 💡 LangChain Demo with Gemma Model

This project is a simple yet powerful Streamlit application demonstrating the integration of LangChain's capabilities with the **Gemma2 Llama model** for conversational AI. The app lets you interact with a helpful assistant capable of answering your questions dynamically and effectively.

---

## 🌟 Features
- **🚀 Gemma2 Llama Model**: Powered by the **Gemma2:2b** model for generating precise and coherent responses.
- **🛠️ LangChain Integration**: Leverages LangChain's robust framework for building conversational AI pipelines.
- **🎯 Dynamic Prompting**: Uses a customizable prompt template for flexible responses.
- **📈 Langsmith Tracking**: Includes tracking features for monitoring and evaluating performance.
- **📦 Streamlit Interface**: User-friendly interface for interactive question-answering.

---

## 🔧 Prerequisites

To run this application, you'll need:
- **Python**: Version 3.7 or higher
- **LangChain API Key**: Required for tracking and project management
- **Streamlit**: For creating the web interface
- **Ollama**: For integrating the Gemma2 Llama model

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/0Xuser100/LangChain-Gemma-Demo.git
cd LangChain-Gemma-Demo
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
- **Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Set Up Environment Variables
- Create a `.env` file in the project root.
- Add the following variables:
  ```plaintext
  LANGCHAIN_API_KEY=your_langchain_api_key
  LANGCHAIN_PROJECT=your_project_name
  ```

---

## 🚀 How to Use

1. **Run the Application**
   ```bash
   streamlit run app.py
   ```

2. **Enter Your Question**
   - Use the input field to type your question.
   - Press Enter, and the assistant will provide a response.

---

## 🗂️ Project Structure
```
LangChain-Gemma-Demo/
├── app.py             # Main application script
├── requirements.txt   # Required dependencies
├── .env.example       # Template for environment variables
├── README.md          # Project documentation
└── resources/         # Placeholder for additional resources
```

---

## 📋 Dependencies

### Key Python Packages
- `streamlit`
- `langchain_community`
- `langchain_core`
- `ollama`
- `dotenv`

Ensure all required packages are included in `requirements.txt`.

---

## 🧪 Example Workflow

1. **User**: "What is the capital of France?"
2. **App**: Calls the **Gemma2** model with the LangChain pipeline.
3. **Response**: "The capital of France is Paris."

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:
- Fork the repository.
- Create a feature branch.
- Submit a pull request with your changes.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 📞 Contact

For questions, suggestions, or feedback:
- **Name**: Mahmoud Abdelhamid  
- **Email**: [mahmoudabdulhamid22@gmail.com](mailto:mahmoudabdulhamid22@gmail.com)  
- **GitHub**: [https://github.com/0Xuser100](https://github.com/0Xuser100)  
- **LinkedIn**: [https://www.linkedin.com/in/mahmoud-abdulhamid-052244230/](https://www.linkedin.com/in/mahmoud-abdulhamid-052244230/)

---

Unleash the potential of conversational AI with LangChain and the Gemma2 Llama model! 🚀
