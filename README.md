## Configuration

Put your API key in the `.env` file

## Running the Indexing pipeline

```bash
python -m graphrag.index --root ./ragtest
```

## Running the Query Engine

```bash
python -m graphrag.query \
--root ./ragtest \
--method global \
"What are the top themes in this story?"
```
