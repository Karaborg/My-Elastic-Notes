# My-Elastic-Notes

1. `docker compose up -d`
2. Find ElasticSearch Token
    1. `docker exec -it elasticsearch bash`
    2. `bin/elasticsearch-create-enrollment-token --scope kibana`
3. Open Kibana at `http://localhost:5601/`
4. Paste the token
5. Get the code from Kibana
    1. `docker exec -it kibana bash`
    2. `./bin/kibana-verification-code`