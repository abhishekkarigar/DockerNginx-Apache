# DockerNginx-Apache

depends_on example
	docker-compose up starts services in dependency order
	docker-compose up <service> starts its dependencies
	docker-compose stop stops services in dependency order. 
	
	depends_on doesnt wait for the services to be ready 