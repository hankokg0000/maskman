# Demo

## Config
1. conda create --name py36 python=3.6
2. conda activatepy36
3. pip install -r requirements.txt

## Table
1. [Model Training](#Model-Training)
2. [API](#API)
3. [Docker Deploying](#Docker-Deploying)

## Model Training
1. DataPreparation.ipynb
2. Preprocessing.ipynb
3. Eval.ipynb

## API
1. python app.py
2. Client.ipynb

## Docker Deploying
1. docker build .
2. docker run --name <container_name> -it -p 80:80 -d <image_name>