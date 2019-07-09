FROM python:2.7-slim
ADD . /code
WORKDIR /code
RUN pip install flask && pip install redis
CMD python app.py

