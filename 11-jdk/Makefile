TAG = tmurakam/centos7-openjdk:11-ea

all: build

build:
	docker build -t ${TAG} .

rmi:
	docker rmi ${TAG}

bash:
	docker run -it --rm ${TAG} /bin/bash

push:
	docker push ${TAG}
