# RAG-Mastery
A complete end-to-end RAG learning repository covering fundamentals to advanced concepts: chunking, embeddings, retrieval, LLMs, agentic AI, LangGraph, GraphDB, multi-agent RAG, vector databases, RAG evaluation, and LangChain implementations.


## Creating venv using uv: 
1. Install uv: ```pip install uv```
2. Creating virtual environment using selected python interpreter: ```uv venv --python 3.11.13```
3. Activate your virtual env: ```.\.venv\Scripts\activate```
4. Install Requirements: ```uv pip install -r requirements.txt```
5. List installed Libraries: ```uv pip freeze```
6. Install single library: ```uv pip install pandas```


## Inorder to use the same kernel through out the different notebooks:
- Run below:
    1. Make sure ipykernel is installed in your uv environment
    ```uv pip install ipykernel```

    2. Register the kernel properly with a clear name
    ```uv run python -m ipykernel install --user --name "RAG-Mastery" --display-name "RAG-Mastery (.venv)"```
- After running the above:
    - Completely close VS Code (not just the window — exit the application fully).
    - Re-open VS Code.
    - Open your project folder (the one containing the .venv folder).
    - Create a new notebook or open an existing one.
    - Click Select Kernel (top right) → You should now clearly see "RAG-Mastery (.venv)" under Python Environments or Jupyter Kernels.
    - Select it once.

- VS Code should remember this kernel for future notebooks in the same workspace.