# Data Analyst Assistant

**Data Analyst Assistant** is a natural language-based interface that helps users interact with and explore their datasets by simply asking questions. Powered by the **LLaMA 3.3-70B-Instruct** model deployed on Azure, this tool allows users to gain insights from data without writing any code.

---

##  Project Description

Data Analyst Assistant simplifies data exploration by combining the power of machine learning and large language models. It reads your dataset and allows you to ask questions such as “What is the average salary?” or “Which job title has the highest salary?” and returns meaningful insights using AI.

The assistant uses the first few rows, column names, and overall metadata to generate accurate, context-aware responses to user questions.

---

## Features

- Ask questions about your dataset using natural language
- Supports summary statistics, column info, shape, and more
- No need for manual coding or querying
- Works with any tabular dataset (CSV)

---

## Tech Stack

- **Python 3.9+**
- **Pandas** for data manipulation
- **Requests** for API integration
- **Azure Inference API** for LLaMA model communication

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/data-analyst-assistant.git
cd data-analyst-assistant
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

3. Set your GitHub token as an environment variable (optional):

```bash
export GITHUB_TOKEN=your_token_here
```

4. Run the script:

```bash
python app.py
```

---

##  How It Works

1. Loads your dataset (CSV file)
2. Extracts key metadata (shape, column names, sample rows)
3. Builds a prompt using this information
4. Sends the prompt to the LLaMA model hosted on Azure
5. Displays AI-generated insights in response to your question

---

## Future Improvements

- Add support for visualizations (charts, plots)
- Interactive web interface with Streamlit or Flask
- Support for uploading datasets dynamically
- Multilingual support for broader usability

---

## About the Developer

Developed by **Abhishek Kushwaha**

- 🔗 [LinkedIn](https://www.linkedin.com/in/abhishek-kushwaha)
- 💻 [GitHub](https://github.com/abhishek10027)

