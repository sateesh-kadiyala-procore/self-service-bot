### Working with this code.

Download an LLM mode from GPT4ALL(https://gpt4all.io/index.html) and place it on `models` folder.

Have test documents for ingestion in `source_documents` folder


`docker compose up` for running postgres.

On psql shell `CREATE EXTENSION VECTOR;`  to create the pgvector extension on Postgres

`python ingest.py`

`python app.py`

Example Request:

`localhost:3000/answer?q=what is what?`


