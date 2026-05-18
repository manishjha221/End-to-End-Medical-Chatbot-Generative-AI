# End-to-End-Medical-Chatbot-Generative-AI

### Steps
```Project repo: https://github.com/manishjha221/End-to-End-Medical-Chatbot-Generative-AI.git
```
### create a virtual env
```bash
conda create -n medibot python=3.10 -y
```

### activate virtual env

```bash
conda activate medibot
```

### step 2 - install the rquirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
