## Python Virtual Environment
- Create virtual environment
  - ``` python -m venv venv ```
- Start environment (from powershell)
  - ``` ./venv/Scripts/Activate.ps1```
- Install packages on Windows
  - ``` pip install -r requirements.txt ```
- Install packages on Ubuntu (and other Linux distributions)
  - ``` pip install -r requirements-ubuntu.txt ```
- Update requirements file
  - ``` pip freeze > requirements.txt ```

## Docker 
- Run docker compose
  - ``` docker compose up -d ```
- Clean up docker compose 
  - ``` docker compose down ```