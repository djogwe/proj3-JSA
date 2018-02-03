FROM python:3.5
MAINTAINER David Jogwe "djogwe@uoregon.edu"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
WORKDIR /vocab
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]

