# Retrieval Augmented Generation (RAG)
# Jupyter notebook setup
Create virtual environment in this directory.

Install packages:
```
pip install -U "huggingface_hub[cli]"
pip install -U torch
pip install stqdm
pip install tqdm
pip install -U sentence-transformers
pip install PyMuPDF
```
# Streamlit UI setup
Download model from Hugging Face:
```
huggingface-cli download sentence-transformers/all-mpnet-base-v2
```

Download spacy's English model:
```
python -m spacy download en_core_web_sm
```

![PDF RAG Demo](img/pdf_rag_ui_preprocessing.png)
