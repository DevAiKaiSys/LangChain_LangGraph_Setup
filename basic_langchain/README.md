# Setup Project

[Install packages in a virtual environment using pip and venv](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## [Install LangChain](https://docs.langchain.com/oss/python/langchain/install)

```bash
pip install -U langchain
```

provides integrations LLMs

```bash
# Installing the OpenAI integration
pip install -U langchain-openai

# Installing the Anthropic integration
pip install -U langchain-anthropic
```

```bash
export OPENAI_API_KEY="<your-openai-api-key>"

export ANTHROPIC_API_KEY="<your-anthropic-api-key>"
```
