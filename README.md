# jenkisn_lesson 
1. echo   "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
2.    $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
3.  sudo apt-get update
4.  sudo apt-get install docker-ce docker-ce-cli containerd.io
5.  docker pull jenkins/jenkins:lts
6.  docker run -d -p 8080:8080 -p 50000:50000 --volume jenkins-docker-cert:/cert/client --volume jenkins-data:/var/jenkins_home --name=jenkins jenkins/jenkins:lts
7.   14  apt install net-tools
8.   15  netstat -antp
9.   16  curl ifconfig.me
10.   17  logs --tail 50 jenkins
11.   22  wget https://apache-mirror.rbc.ru/pub/apache/tomcat/tomcat-10/v10.0.4/bin/apache-tomcat-10.0.4.zip
13.   23  apt install unzip
14.  unzip apache-tomcat-10.0.4.zip
15.  mv apache-tomcat-10.0.4 tomcat_dev
16.  apt update && apt install default-jdk
17. chmod +x ./*
18. "./ startup.sh"
19.  "./startup.sh"
20.   curl localhost:8090
21.   history
22. https://issues.jenkins.io/browse/JENKINS-58687
23.    http://34.123.201.23:8090/webapp/

24. http://34.123.201.23:8090/demo/index.jsp
