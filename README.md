# Deploy Spring boot application into AWS using Jenkins CICD


Add the ec2-user, Jenkins user to the docker group so you can execute Docker commands without using sudo.:

sudo usermod -a -G docker ec2-user
sudo usermod -a -G docker jenkins
