PostgreSQL High-Availability Cluster with Patroni, Etcd & Docker Compose


This project deploys a 3-node PostgreSQL cluster using **Patroni** and **etcd** for automatic failover and high availability. Built and tested using Docker Compose.
Make sure you have a VM or host with Docker & Docker Compose installed


git clone https://github.com/Kalai25-tech/pg-cluster.git

cd pg-cluster/

# Start the cluster
docker-compose up -d


# Cluster Status
docker exec -it patroni1 patronictl list


# Default Credentials

| Parameter | Value    |
| --------- | -------- |
| Username  | postgres |
| Password  | zalando  |


