# piaic-python-assigment


Task1: Docker
-------------

Dockerize python flask application by setting up the uWSGI application server to launch the application and Nginx to act as a front end reverse proxy.


1- Install Docker

2- Install Docker Compose

3- Clone the projecthttps://github.com/Cryptic-Gemini/piaic-python-assigment.git

4- Create two dockerfiles for flask & nginx.

5- Create docker-compose.yaml file to startup multiple containers (flask and nginx) at the same time and automatically connect them together with some form of networking.

6- Build the project (docker-compose up)

7- Bring up the Application in web browser at port 2020.


Task2: kubernetes
---------------
(a)Dockerize python flask application by setting up the uWSGI application server to launch the application and Nginx to act as a front end reverse proxy.

(b)Deploy in kubernetes Pod by using ConfigMap

Requirements:

Create Dockerfiles for each service to build images.
Create docker-compose.yml to run multiple containers together.
Deploy the entire stack with the docker-compose command.
Pushing the docker images to the docker hub.
Create a ConfigMap with the Nginx configuration file.
Create a multi-container Pod (web app and Nginx in separate containers)
Expose the Pod using nodePort service.

Assignment Help
-----------------------------------------------------------------------------------------------------------------------------
1-Download/clone https://github.com/Cryptic-Gemini/piaic-python-assigment.git sample flask A.I application.

2- Application require python installations in your system

3- Go to python-assignment folder open terminal and run 'pip install -r requirements.txt' for packages installations.

4- You can run application using 'python app.py'

5-Application port 2020.

6-You can use application at localhost:2020
