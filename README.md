# AI Report Generation with Docker

This project runs a Jupyter Notebook inside Docker and generates a structured report without external APIs.

## Files

- `AI_Agents_Report_Generation_No_API.ipynb`: Main notebook
- `Dockerfile`: Docker image configuration
- `compose.yaml`: Docker Compose configuration
- `requirements.txt`: Python requirements
- `outputs/`: Generated reports

## Run

```bash
docker compose build
docker compose up
```

Then open:

```text
http://localhost:8888
```

Open the notebook and select **Run All Cells**.

## Stop

```bash
docker compose down
```
