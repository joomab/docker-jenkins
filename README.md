# docker-jenkins

This repository contains all the knowledge from Platzi's Jenkins course.

The first steps:
https://github.com/jenkinsci/docker/blob/master/README.md

docker build -t local-jenkins:latest .

docker run -d --name jenkins-app -v jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 local-jenkins:latest