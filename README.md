# llamaindex-openai-mistral-tagging

This project is an implementation of a tagging system using [llamaindex](https://github.com/run-llama/llama_index), [OpenAI](https://platform.openai.com/), and [Mistral AI](https://docs.mistral.ai). It's designed to tag input text, leveraging the strengths of each AI system. The output of the tagging process is structured using a robust [Pydantic](https://github.com/pydantic/pydantic) model. And it can also operate locally via [Ollama](https://github.com/jmorganca/ollama) for enhanced privacy and security.

## Features
- Integration with llamaindex, OpenAI, and Mistral AI for advanced tagging.
- Customizable Pydantic model for output schema.
- Local AI processing with Ollama for data privacy and security.

## Installation
### Prerequisites
- Python 3.9.x
- OpenAI and MistralAI API keys.
- Ollama instance

### Setup
```bash
pip install -r requirements.txt
```
Follow the [readme](https://github.com/jmorganca/ollama) to set up and run a local Ollama instance.