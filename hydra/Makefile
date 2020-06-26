image_name:=drag0ns3c/hydra

.PHONY: build
build:
	docker build --no-cache -t $(image_name):latest .

.PHONY: push
push:
	docker push $(image_name):latest
