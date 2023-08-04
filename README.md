# Research-Assistant
An AI Powered Research Assistant

Research Assistant is a first draft of a Python application that allows you to chat with relevant research papers which can assist in automating research workflows like literature review, summarizing takeaways, and extracting key information from the papers.

## Installation and Usage
Clone the repository to your local machine.

Install the required dependencies by running the following command:

```pip install -r requirements.txt```

Obtain an API key from OpenAI and add it to the .env file in the project directory.

```OPENAI_API_KEY=your_secrit_api_key```

Alternatively, obtain an API key from HuggingFace and add that to the .env file

```HUGGINGFACEHUB_API_TOKEN=your_secrit_api_key```

Next, run the app.py file using Streamlit CLI

```streamlit run app.py```
