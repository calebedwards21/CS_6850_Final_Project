## Python version
This project has been created using Python 3.10. Older versions of Python 3 may not support the required packages.

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

## Grafana Instructions
1. Install required packages
2. Spin up docker compose
3. Run `main.ipynb` to populate data in postgres database
4. Open Grafana [here](http://localhost:3000)