# FastAPI Backend

## Railway Deployment

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=fastapi)

1. Click the "Deploy on Railway" button above
2. Connect your GitHub account
3. Select this repository and the `staging/githubpages-railway` branch
4. Railway will automatically detect and deploy the FastAPI application

## Environment Variables
No environment variables are required for basic setup.

## Local Development
```bash
python -m uvicorn main:app --reload
```