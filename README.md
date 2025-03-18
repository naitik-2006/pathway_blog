## Usage Instructions

Follow these steps to properly set up and run the Colab notebook:

### 1. Replace `vector_store.py`
Before running the Colab notebook, replace the existing file located at:
```sh
/usr/local/lib/python3.11/dist-packages/pathway/xpacks/llm/vector_store.py
```
with the provided `vector_store.py` file.

### 2. Upload Required Files
Upload the following files to the Colab environment:
- `app_jina.py`
- `app_raptor.py`

### 3. Create Required Directory
Create a folder named `JINA` inside the `/content` directory:
```sh
mkdir /content/JINA
```
Upload all necessary files required for question-answering into this folder.

### 4. Running the Notebook
Run the notebook from the beginning, executing each cell one by one.

- There is a separate example section for **Interleaving** and **Raptor**.
- If needed, you can execute these example cells. Otherwise, you may skip them.

### 5. Running Required Scripts in the Terminal
Before creating the vector store or retriever, ensure that `app_jina.py` is running in the terminal:
```sh
python app_jina.py
```

Whenever the **Interleaving agent** is retrieving, make sure `app_raptor.py` is running in the terminal:
```sh
python app_raptor.py
```

This ensures the required services are available while executing the notebook.

---
Following these steps will ensure smooth execution of the Colab notebook with proper file dependencies.
