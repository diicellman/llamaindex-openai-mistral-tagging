# llamaindex-openai-mistral-tagging

## Description
This project is an implementation of a tagging system using [llamaindex](https://github.com/run-llama/llama_index), [OpenAI](https://platform.openai.com/), and [Mistral AI](https://docs.mistral.ai). It's designed to tag input text, leveraging the strengths of each AI system. The output of the tagging process is structured using a robust [Pydantic](https://github.com/pydantic/pydantic) model.

## Features
List the key features of your project. 

- Integration with llamaindex, OpenAI, and Mistral AI for advanced tagging.
- Customizable Pydantic model for output schema.

## Installation
### Prerequisites
- Python 3.x
- OpenAI and MistralAI API keys.

### Setup
```bash
git clone [your-repo-url]
cd [your-repo-directory]
pip install -r requirements.txt
```
## Output Schema
The output schema of the tagging system is defined using a Pydantic model. This ensures validation, serialization, and documentation of the output data.