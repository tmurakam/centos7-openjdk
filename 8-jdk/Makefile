TAG = tmurakam/centos7-openjdk8

all: build

build:
	docker build -t ${TAG} .

rmi:
	docker rmi ${TAG}

bash:
	docker run -it --rm ${TAG} /bin/bash

push:
	docker push ${TAG}:latest


