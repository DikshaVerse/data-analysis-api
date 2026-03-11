# System Design

The Data Analysis API is designed to process datasets and provide analytical insights through REST API endpoints.

## Components

### API Layer
Built using FastAPI to handle incoming HTTP requests.

### Data Processing Layer
Uses Pandas and NumPy to perform dataset analysis and statistical computations.

### Dataset Layer
Handles dataset storage and loading.

---

## Workflow

1. Client sends request to API endpoint.
2. FastAPI receives and processes the request.
3. Dataset is loaded using Pandas.
4. Required analysis is performed.
5. Results are returned as JSON response.

---

## Technology Stack

- Python
- FastAPI
- Pandas
- NumPy
- Uvicorn (for running the server)
