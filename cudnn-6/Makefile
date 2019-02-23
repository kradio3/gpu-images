build:
	docker build . -t starterkit

run:
	docker run --runtime=nvidia --rm -it starterkit

attach:
	docker exec -it $(shell sh -c "docker ps| grep starterkit" | awk '{print $$1}') /bin/bash
