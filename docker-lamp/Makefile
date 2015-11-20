build:
	docker build -t lamp .

run:
	docker run -d -p 8080:80 -p 3307:3306 -v $$(pwd):/app lamp

stop:
	docker stop $$(docker ps -a -q | head -n1)
