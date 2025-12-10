# Private files Chatbot

Using huggingface and langchain this app offers: -

- **Model Switching:** Easily switch between different Huggingface models as per your requirements.
- **Document Chat:** Chat with your documents, including `(CSV, DOCX, PPTX, PDF)` files. Upload your documents and start querying them.

**Chat with your CSV: -**
![Sample Chat with CSV](Sample_Runs/Chat_with_CSV.jpg)

**Chat with you PDF: -**

![Sample Chat with PDF](Sample_Runs/Chat_with_PDF.png)


## Run

```bash
streamlit run Chatgbt_Ghost.py
```

## Models Used

- hkunlp/instructor-xl (For Embeddings)
- google/flan-t5-xxl
- google/flan-t5-small
- google/flan-t5-base
- mistral-7b-instruct-v0.2.Q4_K_S (For local runs using LlamaCpp)
