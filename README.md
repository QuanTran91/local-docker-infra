docker compose -f local-infra-docker-compose.yaml -p local-infra up --detach

docker compose -f kafka-docker-compose.yaml -p local-kafka up  --detach

docker compose -f elasticsearch-vietname-docker-compose.yaml -p local-es-vietnamese up  --detach
docker compose -f cassandra-docker-compose.yaml -p local-cass up  --detach



Reference:
https://raw.githubusercontent.com/confluentinc/cp-all-in-one/7.5.2-post/cp-all-in-one-kraft/docker-compose.yml