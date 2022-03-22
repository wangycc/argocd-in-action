DOCKER_TAG = "v1"
DOCKER_IMAGE = "wangyichen/flask-demo"

build:
	@docker build -t $(DOCKER_IMAGE):$(DOCKER_TAG) .

push:
	@docker push $(DOCKER_IMAGE):$(DOCKER_TAG)
all: build push

rm:
	@docker rmi $(DOCKER_IMAGE):$(DOCKER_TAG)
.PHONY: build push all rm
