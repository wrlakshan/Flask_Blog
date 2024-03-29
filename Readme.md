## create environment

```bash
python3 -m venv env
```

## activate environment

```bash
source env/Scripts/activate
```

## install flask

```bash
pip install flask
```

## check flask installed version

```bash
python -c "import flask; print(flask.__version__)"
```

## check flask installed version

```bash
python -c "import flask; print(flask.__version__)"
```

## run the application

```bash
export FLASK_APP=app

--dev mode
    export FLASK_ENV=development
    export FLASK_DEBUG=1

flask run
flask run -p 5001
```

## initialization the Database

```bash
python init_db.py
```
