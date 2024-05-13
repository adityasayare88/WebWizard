# WebWizard: The AI-Powered Website Explorer

WebWizard is a revolutionary AI-powered conversational assistant that empowers users to interact with and extract information from websites through natural language dialogues. Leveraging the cutting-edge capabilities of Langchain and state-of-the-art language models, WebWizard seamlessly bridges the gap between humans and the vast expanse of the web.

With an intuitive conversational interface, WebWizard acts as a virtual guide, allowing users to explore websites by simply providing a URL and engaging in natural language conversations. Whether you need to find specific content, perform searches, or gather data, WebWizard's intelligent capabilities make the process seamless and efficient. Built using Python and featuring a user-friendly Streamlit interface, WebWizard represents the future of web exploration and information retrieval, delivering a truly personalized and engaging experience.
## Acknowledgements

- [Langchain](https://python.langchain.com/en/latest/index.html) - A powerful library for building applications with large language models.
- [Streamlit](https://docs.streamlit.io/) - An open-source app framework for creating interactive data visualization and app development.
- [OpenAI](https://platform.openai.com/docs/introduction) - For their groundbreaking work in natural language processing and language models.
- [BeautifulSoup4](https://beautiful-soup-4.readthedocs.io/en/latest/) - A robust library for web scraping and data extraction.
- [Python Community](https://www.python.org/doc/) - For the numerous libraries, resources, and support.
## Screenshots






Here are the key features of the WebWizard project in short bullet points:

- **Natural Language Interaction**: Engage with websites through intuitive conversational queries using natural language processing powered by Langchain and OpenAI's language models.

- **Website Content Exploration**: Seamlessly navigate and extract relevant information from websites by providing the URL and conversing with the AI assistant.

- **Intelligent Information Retrieval**: WebWizard intelligently retrieves and presents the most relevant information based on the user's conversational queries.

- **User-Friendly Interface**: Featuring a clean and interactive Streamlit interface, WebWizard provides a seamless and engaging experience for exploring websites.

- **Web Scraping and Data Extraction**: Leveraging BeautifulSoup4, WebWizard can efficiently scrape and extract data from websites for enhanced information retrieval.
## Optimizations

**Future Scope**: To add functionality of chatting with multiple pdf.

## Run Locally

Clone the project

```bash
  git clone https://github.com/adityasayare88/WebWizard.git
```

Go to the project directory

```bash
  cd project
```

Install dependencies

```bash
 pip install streamlit langchain langchain-openai beautifulSoup4 python-dotenv chromaDB
```

Start the server

```bash
  conda create --name WebWizard python=3.10

  conda activate WebWizard

  Note: Install all the above dependencies only after creating a virtual environment (By activating conda)
```


## Tech Stack

- **Python** - The core programming language used for developing WebWizard.
- **Langchain** - A powerful library for building applications with large language models, providing natural language processing capabilities.
- **OpenAI** - State-of-the-art language models used for generating human-like responses and text understanding.
- **Streamlit** - An open-source app framework for building interactive data visualization and web applications.
- **BeautifulSoup4** - A robust library for web scraping and data extraction from HTML and XML documents.
- **Chroma** - A vector store library used for efficient storage and retrieval of embeddings and text data.
- **python-dotenv** - A library for loading environment variables from a `.env` file, used for securely storing API keys and other sensitive information.

## Running Tests

To run tests, run the following command

```bash
  streamlit run src/app.py
```

