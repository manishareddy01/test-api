to set up virtual environment : python -m venv venv

to activate" venv\scripts\activate.bat

pip install fastAPI uvicorn sqlalchemy pymysql

to run the server: uvicorn main:app --reload

make changes in db url, change root:root with your username:pwd and BlogApp with your dbschema
