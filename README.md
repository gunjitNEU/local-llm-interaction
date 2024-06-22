# Setting up LLMs on a Local Machine

## Objective
The purpose of this project is to set up and interact with large language models (LLMs) directly on our local machine. In this project, we use Ollama as the LLM framework and its different models.

## Project Structure
- **video/**: Contains [video](video) presentation.You can also watch the video on [YouTube](https://youtu.be/srly6hArtrg).

## Setting up LLMs
We begin by setting up the LLMs on our local machines:

### Installation Instructions:
### macOS
1.	Download the [Ollama installer for macOS](https://ollama.com/download/Ollama-darwin.zip).
2.	Extract the downloaded ZIP file.
3.	Open Terminal and navigate to the extracted folder.
4.	Run the following command to install Ollama: `./install.sh`

### Windows Preview
1.	Download the [Ollama for Windows](https://ollama.com/download/OllamaSetup.exe) setup executable.
2.	Run the downloaded executable file and follow the on-screen instructions to complete the installation.

### Linux
1.	Open a terminal window.
2.	Run the following command to install Ollama: `curl -fsSL https://ollama.com/install.sh | sh`

### After installing Ollama, you can interact with it via the curl command:

- To run a model: `ollama run [Model-Name]`
- Wait for the model to be pulled
- Input your prompt

For further instructions, visit the [Ollama GitHub page](https://github.com/ollama/ollama).

## Choosing Models
We compare two different Ollama models: llama 3 and llama3-chatqa.

1. **llama 3**
Description: An advanced language model with 8 billion parameters, offering robust performance and a wide range of capabilities in a compact size of 4.7 GB. Suitable for diverse natural language processing tasks.
Command: `ollama run llama3`

2. **gemma**
Gemma is a family of lightweight, state-of-the-art open models built by Google DeepMind. Updated to version 1.1
Command: `ollama run gemma`

## Acknowledgment
This LLM model was originally published by [Ollama](https://github.com/ollama/ollama).