FROM python:2.7
LABEL maintainer="Alma Vita Sophia"
EXPOSE 3111

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt

# command to run on container start
CMD [ "python", "init_db.py" ]
CMD [ "python", "app.py" ]
