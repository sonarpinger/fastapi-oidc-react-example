# Getting Started

## Dependencies
```bash

python3 -m venv
source venv/bin/activate
pip install httpx itsdangerous jinja2 authlib fastapi uvicorn[standard] pydantic[dotenv] websockets pydantic_settings
mkdir static
mkdir templates

cp env-example .env #Modify settings
```
