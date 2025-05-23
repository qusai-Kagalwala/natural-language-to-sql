# Natural Language to SQL 🗣️➡️🗃️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![AI](https://img.shields.io/badge/AI-FF6B6B?style=for-the-badge&logo=openai&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📝 Short Description
A Streamlit web application that converts natural language queries into SQL statements using AI. Simply describe the data you want in plain English, and the app generates the corresponding SQL query for your SQLite database.

## 📖 About
This project bridges the gap between non-technical users and database querying by leveraging AI language models. Instead of learning complex SQL syntax, users can describe what data they need in natural language, and the application automatically generates the appropriate SQL query. Built for educational purposes to demonstrate practical applications of large language models in database management.

## ✨ Features
• Convert plain English queries to SQL statements
• AI-powered generation using DeepSeek R1 model
• Interactive web interface with Streamlit
• Automatic database schema detection
• Clean SQL output with reasoning token removal
• Real-time query generation
• SQLite database support

## 🛠️ Tech Stack / Built With
• **Python** - Core programming language
• **Streamlit** - Web application framework
• **LangChain** - AI framework for LLM applications
• **Ollama** - Local LLM deployment
• **DeepSeek R1:8B** - AI model for text-to-SQL conversion
• **SQLAlchemy** - Database toolkit and ORM
• **SQLite** - Database engine

## 🚀 Getting Started

### Prerequisites
• Python 3.8 or higher
• Ollama installed on your system
• DeepSeek R1:8B model

### Installation
1. Clone the repository
```bash
git clone https://github.com/qusai-Kagalwala/natural-language-to-sql.git
cd natural-language-to-sql
```

2. Install dependencies
```bash
pip install streamlit langchain-ollama langchain-core sqlalchemy
```

3. Setup Ollama and pull the model
```bash
ollama pull deepseek-r1:8b
```

4. Ensure your SQLite database file `testdb.sqlite` is in the project directory

## 💻 Usage
1. Start the application
```bash
streamlit run text-to-sql.py
```

2. Open your browser to `http://localhost:8501`

3. Enter natural language queries like:
   - "Show me all customers from New York"
   - "Find total sales by category"
   - "List recent employee hires"

4. View the generated SQL query in the output

## 🤝 Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements
• [Streamlit](https://streamlit.io/) - Web app framework
• [LangChain](https://langchain.com/) - AI framework
• [Ollama](https://ollama.ai/) - Local LLM deployment
• [DeepSeek](https://deepseek.com/) - R1 language model
• [SQLAlchemy](https://sqlalchemy.org/) - Database toolkit
