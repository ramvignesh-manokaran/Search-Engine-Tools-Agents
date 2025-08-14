# Search Engine with tools and Agents

- Tools like Arxiv, Wikipedia and DuckDuckGoSearchRun are used. 
- Have also tried custom Retriever to retrieve info from Langsmith website.
- LLM interacts with these tools to answer user query.
- Agents are used to interact with above tools.
- we have used `StreamlitCallbackHandler` to display the thoughts and actions of an agent in an interactive Streamlit app.

## Setting Up environment

1.Run below command to create python environment
 ```bash
conda create -p venv python==3.10 -y  
```

2. Create requirements.txt file with required libraries.

3. Activate environment by running below command.
 ```bash
conda activate venv/ 
```
4. Install all libs in requirements.txt using below command.
 ```bash
pip install -r requirements.txt
```

5. Create an .env file with below keys before executing ipynb files. 
    LANGCHAIN_API_KEY=""
    LANGCHAIN_PROJECT=""
    OPENAI_API_KEY=""
    GROQ_API_KEY=""

6. Run 'app.py' file using below command from respective folder.
 ```bash
streamlit run app.py 
```
