# DockerComposeFofKraft

Docker compose for Kraft (Kafka with no zoo keeper)
You don't need to build, just run :) 

*Installing*
1. Gen clusterid
   ```docker run --rm confluentinc/cp-kafka:latest kafka-storage random-uuid```
2. Change your cluter id on doker-compose.yaml file
3. Run your cluster
   '''docker compose up -d'''
