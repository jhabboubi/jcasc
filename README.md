#Dockerize jenkins configuration as code

[Documentation and Instructions](https://www.digitalocean.com/community/tutorials/how-to-automate-jenkins-setup-with-docker-and-jenkins-configuration-as-code)
JCASC refrences `server_ip:8080/configuration-as-code/reference`

- clone repo and cd into it
- docker build -t jenkins:jcasc .
- docker run -it --name jenkins --rm -p 8080:8080 --env JENKINS_ADMIN_ID=admin --env JENKINS_ADMIN_PASSWORD=password jenkins:jcasc
