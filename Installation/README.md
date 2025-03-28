# Setting Up Conda Section

conda env list
conda create -n langchain python=3.12.4 -y
## Activate Environment
conda activate langchain

## Deactivate Environment
conda deactivate langchain

## Remove Environment
conda create -n langchain python=3.12.4 -y

## Install Requirements
ls
cat requirements.txt
pip install -r requirements.txt

# Setting up Ollama

## Installation

curl -fsSL https://ollama.com/install.sh | sh

## Pull models
Syntax ollama pull <modelname>
eg ollama pull llama3.2:1b