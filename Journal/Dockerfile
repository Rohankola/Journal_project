FROM python:3.7

WORKDIR /Users/Rohankola/PycharmProjects/Journal

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 5000

CMD [ "python", "main.py" ]