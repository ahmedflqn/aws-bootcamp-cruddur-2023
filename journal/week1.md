# Week 1 — App Containerization

## Required homework
### Containerzie applications
I have created docker files for both frontend and backend and used docker compose to run them you can find files here [backend](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/backend-flask/Dockerfile), [frontend](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/frontend-react-js/Dockerfile), [docker-compose](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/docker-compose.yml)
![Running app](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/running%20app.PNG?raw=true) 

 ### Document the Notification Endpoint for the OpenAI Document
 created a notification feature by writing a backend endpoint and creating a react page 
 ![Implementing notifications](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/notifications.PNG?raw=true)
### Run DynamoDB Local Container and ensure it works

 added DynamoDB to docker compose file and run it locally
 ![Get records from table](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/Get%20records%20from%20table.PNG?raw=true)
![list tables](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/List%20table.PNG?raw=true)

### Run Postgres Container and ensure it works
 added Postgres to docker compose file and run it locally
![enter image description here](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/Postgres.PNG?raw=true)

## Homework challenges
    
-   Push and tag a image to DockerHub (they have a free tier)
1.  `docker login --username username`
    
2.  `docker tag my-image username/my-repo`
    
3.  `docker push username/my-repo`
    ![enter image description here](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/dockerhub.PNG?raw=true)
-   Use multi-stage building for a Dockerfile build
![Multi stage dockerfile](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/multistage.PNG?raw=true)
    
-   Implement a healthcheck in the V3 Docker compose file
added health check to docker compose file
    ![Health check](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/health%20check.PNG?raw=true)
    
    
-   Launch an EC2 instance that has docker installed, and pull a container to demonstrate you can run your own docker processes.List item
![run docker on ec2](https://github.com/ahmedflqn/aws-bootcamp-cruddur-2023/blob/main/journal/assets/ec2.PNG?raw=true)
