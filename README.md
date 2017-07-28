## Build:
	docker build -t aker/lantern .
	
## Use Case 1: auto running when docker start

	docker run -itd --restart=always --name lantern -p 3128:3128 aker/lantern
	
## Use Case 2: unlimited stream

	docker run --rm --name lantern -p 3128:3128 aker/lantern

