
# DKG-LLM Implementation

This project implements a **DKG-LLM (Domain Knowledge Graph - Large Language Model)** integration. It leverages the synergy between Knowledge Graphs (KG) and LLMs to enhance domain-specific reasoning, reduce hallucinations, and provide grounded, accurate responses.

##  Overview

The goal of this project is to create a robust system where an LLM is augmented by a Domain Knowledge Graph. By retrieving structured data from the graph, the model gains access to expert-level information that standard LLMs might lack or misinterpret.

## Features

- **Knowledge Graph Integration:** Connects domain-specific facts and relationships to the LLM workflow.
- **RAG Implementation:** Utilizes Retrieval-Augmented Generation to ensure responses are grounded in facts.
- **Scalable Architecture:** Designed with modular components for easy integration with various LLM backends (e.g., OpenAI, HuggingFace models).
- **Domain-Specific Reasoning:** Improved accuracy for specialized queries.


 Prerequisites
Before running the project, ensure you have the following installed:

Python 3.9+
Git
API Keys for your preferred LLM provider (e.g., OpenAI)
 Installation
Clone the repository:
bash
   git clone https://github.com/SabaHesaraki/DKG-LLM-Implementation.git
   cd DKG-LLM-Implementation
   
Create and activate a virtual environment:
bash
   python -m venv venv
   # On Windows:
   .\venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   
Install dependencies:
bash
   pip install -r requirements.txt
   
 Usage
Configure your environment variables (e.g., create a .env file with your OPENAI_API_KEY).
Run the main script/notebook to initiate the pipeline:
bash
   python main.py
   
Contributing
Contributions are welcome! If you have suggestions for improvement or find any bugs, feel free to open an issue or submit a pull request.

 Author
Saba Hesaraki  , Maryam Abdollahi Shamami , Ali Sarabadani

GitHub Profile

License
This project is open-source and available under the MIT License.
