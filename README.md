# mini_rag 

this is a minimal implementation of the RAG model for question asnwering. 


## Requirments 

- Python 3.8 or later 

#### Install Python using MiniConda 

1) Download and install MiniConda from [here](https://www.anaconda.com/docs/getting-started/miniconda/install/windows-gui-install)

2) Create new enviroment using the following command:
```bash
$ conda create -n mini-rag python=3.8
```
3) Activate the enviroment:
```bash
$ conda activate mini-rag
```

## Installation 

### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash 
$ cp .env.example .env
```

set your environment variabkes in the `.env` file. like `OPENAI_API_KEY` value.

## Run the FastAPI server 

```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000 
```

