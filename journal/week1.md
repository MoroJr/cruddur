# Week 1 — App Containerization

## Homework Challenges
  - Run the dockerfile CMD as an external script
  ![Dockerfile as CMD](./assets/external_dockerfile_cmd.png)
  
  - Push and tag a image to DockerHub (they have a free tier)
    ![Dockerfile as CMD](./assets/dockerhub-1.png)
    ![Dockerfile as CMD](./assets/dockerhub-2.png)


## Tasks
  - Containerize Application (Dockerfiles, Docker Compose)
    - [Frontend Dockerfile](https://github.com/MoroJr/cruddur/blob/main/frontend-react-js/Dockerfile)
    - [Backend Dockerfile](https://github.com/MoroJr/cruddur/blob/main/backend-flask/Dockerfile)
    - [Docker compose](https://github.com/MoroJr/cruddur/blob/main/docker-compose.yml)
  - Document the Notification Endpoint for the OpenAI Document
    - [Notifications OpenAI Documentation](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-0aadfd2f8f82173d1d5766888ec2335e880e49c38c936e5ecb84da6ebf6220a9)
  - Write a Flask Backend Endpoint for Notifications
    - [Backend Endpoint for Notifications](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-0014cc1f7ffd53e63ff797f0f2925a994fbd6797480d9ca5bbc5dc65f1b56438R72)
    - Fixed [data_show_activity endpoint](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-0014cc1f7ffd53e63ff797f0f2925a994fbd6797480d9ca5bbc5dc65f1b56438R114)
    - Added @cross_origin to all endpoints (including GET) - there were some CORS issues
  - Write a React Page for Notifications	
    - Added [Notifications path](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-d95064ed8d1ffc32d8b4ed5cd5a797264a6089d239527f9fa67e60e868600cef)
    - Added [Notifications page](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-b2255ce048e85fd16283750bd3c8f764ba4f3b93fb68446a20f2e77d3b9dc305)
  - Run DynamoDB Local Container and ensure it works	
    - Added [DynamoDB](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-e45e45baeda1c1e73482975a664062aa56f20c03dd9d64a827aba57775bed0d3R20) to docker-compose
    - Created a table & added some items to it & listed them
    - ![DynamoDB Results](./assets/dynamodb.png)
  - Run Postgres Container and ensure it works	
    - [Added postgres client to yaml](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-370a022e48cb18faf98122794ffc5ce775b2606b09a9d1f80b71333425ec078eR12)
    - [Added postgres to docker compose](https://github.com/MoroJr/cruddur/commit/666d57134f1727126a1946a6b14db46d017008a4#diff-e45e45baeda1c1e73482975a664062aa56f20c03dd9d64a827aba57775bed0d3R32)
    - ![Postgresql client](./assets/postgresql.png)
