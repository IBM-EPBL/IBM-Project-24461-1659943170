FROM python:3.10
ENV sendGripdAPI ---------------------------------
ENV sendgridSender -------------------
LABEL maintainer="Sriram H,ramsri1702@gmail.com"
COPY ./requirements.txt /app/requirements.txt
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["python" , "app.py" ]

#  docker build - < Dockerfile