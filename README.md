# bop-docker-compose
BOP project docker compose
* 1.) Harvesting Data:
  
  - TU Berlin
  ````
  curl -i -X PUT -H "X-API-Key: yourRepoApiKey" -H "Content-Type: text/turtle" --data @bop-tuberlin.ttl localhost:8082/catalogues/bop-tuberlin ````
