## About the Project:
```
This is the the Indian Second-Hande Bike sales Price Prediction Project. In this Project We Predict the Bike Price according
to there Age,Kms-Ride,Engine-CC and Brand.
This whole code is done on Modular Form in VsCode and i have also Dockerise the whole Project also.
```

## To write in Docker File:
```
FROM python:3.8-slim-buster
WORKDIR /app
COPY . /app

RUN apt update -y && apt install awscli -y

RUN apt-get update && pip install -r requirements.txt  

CMD ["python3","app.py"]

```


## To Build The Docker in the Local:
```
docker build -t name-docker:latest .
```
## Some Docker Command:
```
docker login  -->    To login for first time in terminal
docker images -->    To See the name and size of the docker-image which had been created
```
