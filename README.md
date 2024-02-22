# langchain-gemma-ollama-chainlit
Simple Chat UI using Gemma model via Ollama, LangChain and Chainlit

### Open Source in Action 🚀
- [Gemma](https://ai.google.dev/gemma/docs/model_card) as Large Language model via [Ollama](https://ollama.com/)
- [LangChain](https://www.langchain.com/) as a Framework for LLM
- [LangSmith](https://smith.langchain.com/) for developing, collaborating, testing, deploying, and monitoring LLM applications.
- [Chainlit](https://docs.chainlit.io/langchain) for deploying.

## System Requirements

You must have Python 3.10 or later installed. Earlier versions of python may not compile.

## Steps to Replicate 

1. Fork this repository and create a codespace in GitHub as I showed you in the youtube video OR Clone it locally.
   ```
   git clone https://github.com/sudarshan-koirala/langchain-gemma-ollama-chainlit.git
   cd langchain-gemma-ollama-chainlit
   ```

2. Create a virtualenv and activate it
   ```
   python3 -m venv .venv && source .venv/bin/activate
   ```

3. OPTIONAL - Rename example.env to .env with `cp example.env .env`and input the environment variables from [LangSmith](https://smith.langchain.com/). You need to create an account in LangSmith website if you haven't already.
   ``` 
   LANGCHAIN_TRACING_V2=true
   LANGCHAIN_ENDPOINT="https://api.smith.langchain.com"
   LANGCHAIN_API_KEY="your-api-key"
   LANGCHAIN_PROJECT="your-project"
   ```

4. Run the following command in the terminal to install necessary python packages:
   ```
   pip install -r requirements.txt
   ```

5. Run the following command in your terminal to start the chat UI:
   ```
   chainlit run langchain_gemma_ollama.py
   ```

## Disclaimer
This is test project and is presented in my youtube video to learn new stuffs using the available open source projects and model. It is not meant to be used in production as it's not production ready. You can modify the code and use for your usecases ✌️
