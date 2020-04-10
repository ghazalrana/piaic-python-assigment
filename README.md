# piaic-python-assigment


Task1 : (Docker + Python)
-------------------------

Dockerize python flask application.

1- Clone the project https://github.com/Cryptic-Gemini/piaic-python-assigment.git

2- Create a Dockerfile

3- Bring up the Application in web browser at port 2020.


Task2: (Heroku + python + gunicorn)
-----------------------------------

Deploying python app on Heroku using gunicorn.

1- Clone the project https://github.com/Cryptic-Gemini/piaic-python-assigment.git

2- Install heroku CLI using: $ sudo snap install --classic heroku

3- Create a Procfile

4- After you install the CLI, run the heroku login command. ($ heroku login).

5- Initialize a local Git repository and commit your application code to it.

6- Create a Heroku app:  ($ heroku create app-name)

7- Add a remote to your local repository: $ heroku git:remote -a app-name

8- Use the git push command to deploy your app on Heroku: $ git push heroku master 

9- You will find your app running as:  https://app-name.herokuapp.com/


Task3: (Docker Compose + python + uWSGI + nginx)
-----------------------------------------------

Dockerize python flask application by setting up the uWSGI application server to launch the application and Nginx to act as a front end reverse proxy.


1- Install Docker

2- Install Docker Compose

3- Clone the project https://github.com/Cryptic-Gemini/piaic-python-assigment.git

4- Create two dockerfiles for flask & nginx.

5- Create docker-compose.yaml file to startup multiple containers (flask and nginx) at the same time and automatically connect them together with some form of networking.

6- Build the project (docker-compose up)

7- Bring up the Application in web browser at port 2020.

Task4 :(Heroku + python + uWSGI + nginx)
-----------------------------------------

Python app (AI model) using uwsgi and nginx deployed on heroku

1- Clone the project https://github.com/naveed-rana/PIAIC-Faisalabad-Kubernetes-Assignment-01

2- Install heroku CLI using: $ sudo snap install --classic heroku

3- Set http-socket to :$(PORT) in uWSGI Configuration File

4- Make a Procfile to start your uWSGI instance.

5- After you install the CLI, run the heroku login command. ($ heroku login).

6- Initialize a local Git repository and commit your application code to it.

7- Create a Heroku app:  ($ heroku create app-name)

8- Add a remote to your local repository: $ heroku git:remote -a app-name

9- Use the git push command to deploy your app on Heroku: $ git push heroku master 

10- You will find your app running as:  https://app-name.herokuapp.com/


Task5: kubernetes
------------------
(a)Dockerize python flask application by setting up the uWSGI application server to launch the application and Nginx to act as a front end reverse proxy.

(b)Deploy in kubernetes Pod by using ConfigMap

Requirements:

1-Create Dockerfiles for each service to build images.

2-Create docker-compose.yml to run multiple containers together.

3-Deploy the entire stack with the docker-compose command.

4-Pushing the docker images to the docker hub.

5-Create a ConfigMap with the Nginx configuration file.

6-Create a multi-container Pod (web app and Nginx in separate containers)

7-Expose the Pod using nodePort service.

Assignment Help
-----------------------------------------------------------------------------------------------------------------------------
1-Download/clone https://github.com/Cryptic-Gemini/piaic-python-assigment.git sample flask A.I application.

2- Application require python installations in your system

3- Go to python-assignment folder open terminal and run 'pip install -r requirements.txt' for packages installations.

4- You can run application using 'python app.py'

5-Application port 2020.

6-You can use application at localhost:2020
