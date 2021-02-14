#Dockerize jenkins configuration as code

[Documentation and Instructions](https://www.digitalocean.com/community/tutorials/how-to-automate-jenkins-setup-with-docker-and-jenkins-configuration-as-code)
JCASC refrences `server_ip:8080/configuration-as-code/reference`

- clone repo and cd into it
- docker build -t jenkins:jcasc .
- docker run -it --name jenkins --rm -p 8080:8080 --env JENKINS_ADMIN_ID=admin --env JENKINS_ADMIN_PASSWORD=password jenkins:jcasc

# [Vagrant vs. Terraform](https://www.vagrantup.com/intro/vs/terraform)

#Automate your virtual lab environment with Ansible and Vagrant
[Documentation and Instructions](https://www.the-digital-life.com/automate-ansible-vagrant/)
[Same YouTube Video](https://www.youtube.com/watch?v=7Di0twyxw1M)
[github repo vagrant-boilerplates](https://github.com/xcad2k/vagrant-boilerplates)
[Ansible Vagrant Examples](https://github.com/geerlingguy/ansible-vagrant-examples)

- Requirements 
  - Virtual Box
  - Ansible
  - Vagrant