# ML-project
1st ML project



conda create -p venv python==3.7 -y

to setup CI/CD pipeline

1. heroku email= ashshukla7400@gmail.com
2.api key = e8ab9618-96f2-465c-9f09-d032424fb647
3. app name = ml-regression-a

build docker image 

docker build -t <image_name>:<tagname> .

list docker image:-

docker images

to run docker image 

docker run -p 5000:5000 -e PORT=5000 2a9f171280f1