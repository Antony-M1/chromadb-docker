# ChromaDB
ChromaDB is an open-source database developed for storing and using vector embeddings. These embeddings are compact data representations often used in machine learning tasks like natural language processing. ChromaDB serves several purposes: Efficiently storing and managing collections of embeddings and their metadata.

* **Overview**: Chroma is a vector database designed for high-dimensional vector storage and search.
* **Features**: High performance, simple API, integration with various machine learning frameworks.
* **Use Cases**: Semantic search, recommendation systems, image and video search.

![image](https://github.com/Antony-M1/chromadb-docker/assets/96291963/26144926-23aa-4061-9fce-4ee220ee3007)


**Run ChromaDB**

To run the ChromaDB, clone the repository and run the command
```
docker compose up -d
```
The chromadb runs on port `8000`.

<details>
    <summary><h3>Play With Python</h3></summary>

## Prerequisites
* Python 3.10

### Step:
Create a `environment` and activate the `environment` and install the `requirements.txt` packages

```
python3.10 -m venv .venv
```
```
source .venv/bin/activate
```
```
pip install -r requirements.txt
```

in the `main.ipynb` file contains all the code
</details>