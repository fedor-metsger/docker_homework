FROM python:3

WORKDIR /app

COPY . .

RUN . venv/bin/activate

RUN pip install -r requirements.txt

RUN ./manage.py migrate

CMD ./manage.py runserver 0.0.0.0:80
