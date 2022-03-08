# Learning How to Learn

A responsive web page and CSS animation. This page describes different study techniques and methods along with resources to learn more.

CSS file structure done according to BEM Methodology.

---

**[Live Site](https://deserie-how-to-learn.netlify.app/)**

---

## CI/CD Pipeline

1. I provisioned an Ubuntu 20.04 server on AWS, and installed Jenkins and Ansible on it using the following commands:

```
sudo wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
sudo echo 'deb http://pkg.jenkins.io/debian-stable binary/' | sudo tee -a /etc/apt/sources.list.d/jenkins.list
sudo apt-add-repository ppa:ansible/ansible -y
sudo apt-get update
sudo apt install wget curl git python3-minimal ansible -yq
sudo apt-get -y install default-jre
sudo apt-get -y install jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins
netstat -tnlp
sudo lsof -i:8080
```

![](/images/j1.png)

![](/images/j2.png)

---
