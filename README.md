# HighLoadDistributedSystems
Repo for Highly Loaded Distributed Systems labs

## Team members (KA-03мп)

- Климчук Ярослав
- Кочмар Катерина

### Lab1 - Docker

#### Commands
##### Main commands that we need:

- Start docker on Ubuntu - ```sudo sevice docker start```
- Compose and run multi-container Docker applications - ```sudo docker-compose up```
- Compose, run and scale multi-container Docker applications - ```sudo docker-compose up --scale {server name}=3```

#### Task 1

- cd Lab1_Docker/Task1 - go into right directory
- sudo docker-compose up - compose and run Docker application

#### Task 2

- cd Lab1_Docker/Task2 - go into right directory
- sudo docker-compose up - compose and run Docker application

#### Task 3

- cd Lab1_Docker/Task3 - go into right directory
- sudo docker-compose up - compose and run Docker application

#### Task 4

- cd Lab1_Docker/Task4 - go into right directory
- sudo docker-compose up --scale lite_server=3 --scale json_server=3 - compose and run Docker application

#### Task 5

- Run commands that are listed above
- Open Postman and run send GET-queries: http://localhost:8080/lite_server/, http://localhost:8080/json_server/profile, http://localhost:8080/json_server/posts, http://localhost:8080/json_server/comments
- Save the results into file Task5/query_results.txt
- cd Lab1_Docker/Task5 - go into right directory
- cat query_results.txt - check file content


