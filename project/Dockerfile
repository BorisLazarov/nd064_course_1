FROM python:3.9

WORKDIR /app
COPY ./techtrends .

RUN pip install -r requirements.txt

EXPOSE 3111

CMD python init_db.py && python app.py