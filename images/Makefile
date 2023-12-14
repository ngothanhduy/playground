APPLICATION_NAME ?= base
GIT_HASH = $(shell git rev-parse --short HEAD)

build:
	@echo "Build ${APPLICATION_NAME}..."
	@docker build --tag ${APPLICATION_NAME}:${GIT_HASH} -f Dockerfile.${APPLICATION_NAME} .

# packer_build:
# 	@docker run -it --rm ${APPLICATION_NAME}:${GIT_HASH} sh -c "packer build "