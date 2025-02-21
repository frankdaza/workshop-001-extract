# workshop-001-extract
Maestría en Inteligencia Artificial y Ciencia de Datos, clase ETL - Workshop -001: Extract

## Follow these steps before running your notebook (Mac OS X - M1)


#### 1. Creating a Python Environment:
```bash
$ python3 -m venv venv
```

#### 2. Activate the Python environment:
```bash
$ source venv/bin/activate
```

#### 3. Install dependencies from requirements.txt file:
```bash
$ pip install -r requirements.txt
```

#### 4. Make a copy of the .env.example file to .env and add the necessary settings:
```bash
$ cp .env.example .env
```

#### 5. Raise the local PostgreSQL database:
```bash
$ docker compose up -d
```

## Optional

#### 6. Shutdown/stop local PostgreSQL database:
```bash
$ docker compose down
```

#### 7. Disable Python environment:
```bash
$ deactivate
```