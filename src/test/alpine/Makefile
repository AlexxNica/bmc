BMC = /opt/bmc/bin/bmc
DOCKER_IMAGE_NAME = alpine.bmc

all:
	sudo docker build -t $(DOCKER_IMAGE_NAME) .
	$(BMC) pull --nopull $(DOCKER_IMAGE_NAME)
