FROM python:3.10

WORKDIR /payload_generatorApp

COPY ./payload_generator /payload_generatorApp

RUN pip install --upgrade pip
RUN pip3.10 install -r requirements.txt

CMD [ "python3.10", "app.py" ]
