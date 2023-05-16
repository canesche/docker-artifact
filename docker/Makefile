docker-x86:
	docker build -t docker-artifact -f Dockerfile.x86 .

x86-run:
	docker run -ti docker-artifact

docker-arm:
	docker build -t docker-artifact -f Dockerfile.arm .

arm-run:
	docker run -ti docker-artifact

docker-cuda:
	docker build -t docker-artifact -f Dockerfile.cuda .

cuda-run:
	docker run -it --gpus all docker-artifact
