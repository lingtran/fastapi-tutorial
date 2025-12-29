## Set up virtual environment
### `python3 -m venv .venv`
Creates a virtual environment

### `source .venv/bin/activate`
Activates new virtual environment

### `which python3`
Checks the virtual environment is active. Should return `$ <project path>/.venv/bin/python3`

### `python3 -m pip install --upgrade pip`
Upgrades `pip`

### `deactivate`
Exists virtual environment.

## Install dependencies

### `pip3 install -r requirements.txt`

## Run program

### With python - `python3 main.py`
Runs program inside of virtual environment

_Prerequisites:_
 _* Virtual environment is activated._
 _* Dependencies are installed._

### With FastAPI - `fastapi dev main.py`
Runs the live server

#### [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
Automatic, interactive documentation (integrating Swagger UI)