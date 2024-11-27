# PDF Chatter
PDF Chatter is a robust AI-powered tool designed to interact with PDF documents. By leveraging state-of-the-art Large Language Models (LLMs), this project enables users to query PDFs in natural language, extract insights, and retrieve relevant information seamlessly.

## Key Features
Natural Language Querying: Ask questions about your PDFs and get accurate, context-aware answers.
Efficient Processing: Uses advanced inferencing with Groq for high-speed, scalable AI performance.
State-of-the-Art LLM: Built on the powerful Llama 3.1 model, ensuring nuanced understanding of text.

### 1. Installation
* Clone the repository:
```
bash
git clone https://github.com/your-repo/pdf-chatter.git  
cd pdf-chatter
 ```
### 2. Set up the environment:

* Install required dependencies:
```
bash
pip install -r requirements.txt
```
* Configure your Groq setup for inferencing.
### 3. Add your model:

* Make sure you have access to Llama 3.1 and set it up in the project. Here we use Ollama to download the llama model locally.
```
bash
ollama run llama3.1
```

### 4. Usage
* Start the application (here we use streamlit to run the app):
```
bash
streamlit run app.py
```

* Upload PDFs: Use the UI to upload one or more PDFs.

Ask your questions: Input queries in natural language to get insights from the uploaded documents.

## Roadmap
* Implement enhanced summarization capabilities.
* Add support for extracting tables and images.
* Enable integration with cloud storage systems (e.g., Google Drive, Dropbox).
* Support for multilingual document querying.

## Contributing
 * We welcome contributions to improve PDF Chatter. Feel free to submit issues or pull requests.
