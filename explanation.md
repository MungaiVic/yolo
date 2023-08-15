# IP 3 Project

- This is the IP 3 project at Moringa School.
- It explains the reasoning behind the choices made in the project.

## Order of execution of tasks

- A role was created to prepare the server for the application.
- This involved installing git, docker(and other dependancies), python and docker-compose.
- This was to be able to make the server ready to run the application.
- Also, the implementation of the role was to ensure that the role can be used elsewhere without any issues.

## Deployment to GKE

- I used Statefulsets for the database as it is a stateful application. This means that the data is persistent.
- I used a deployment for the backend as it is a stateless application. This means that the data is not persistent in this case.
- The backend service type was changed to LoadBalancer to make it accessible from outside the cluster.
