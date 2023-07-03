# bop-docker-compose
This project consists of docker compose files of the Berlin Open Science platform under the [Berlin University Alliance](https://www.berlin-university-alliance.de/) project.

The project is based on [piveau](https://www.piveau.de/en/), which is a data management platform for the public sector
* 1.) Harvesting Data:
  
  - TU Berlin
  ````
  curl -i -X PUT -H "X-API-Key: yourRepoApiKey" -H "Content-Type: text/turtle" --data @bop-tuberlin.ttl localhost:8082/catalogues/bop-tuberlin ````
