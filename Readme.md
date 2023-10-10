8.3.1.	LAB1 – Basic commands
D:\DEVOPS_TRAINING\8_Docker_K8S\Docker_LA.pdf
8.3.2.	LAB2 – Static Website
1)	# docker run -p 8080:80 prakhar1989/static-site
2)	Open browser http://18.212.19.146:8080/ 
8.3.3.	LAB3 – Sample Python Program
1)	Reference - https://gist.github.com/ashish-mj/
2)	# git clone https://github.com/JagdishMane/python_docker.git
3)	# cd python_docker
4)	# docker build -t pythonflask:v1 .
5)	# docker run -d --name mysite -p 8080:5000 pythonflask:v1
6)	Open Browser to access the application http://<public-ip>:8080
