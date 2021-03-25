# jenkisn_lesson
    4  echo   "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
    5    $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
    6  sudo apt-get update
    7  sudo apt-get install docker-ce docker-ce-cli containerd.io
    8  dicker --version
    9  docker --version
   10  docker pull jenkins/jenkins:lts
   11  docker run -d -p 8080:8080 -p 50000:50000 --volume jenkins-docker-cert:/cert/client --volume jenkins-data:/var/jenkins_home --name=jenkins jenkins/jenkins:lts
   12  docker ps
   13  spt install net-tools
   14  apt install net-tools
   15  netstat -antp
   16  curl ifconfig.me
   17  logs --tail 50 jenkins
   18  docker logs --tail 50 jenkins
   19  docker ps
   20  apt upsate && default-jdk
   21  apt update && default-jdk
   22  wget https://apache-mirror.rbc.ru/pub/apache/tomcat/tomcat-10/v10.0.4/bin/apache-tomcat-10.0.4.zip
   23  apt install unzip
   24  unzip apache-tomcat-10.0.4.zip
   25  ls
   26  mv apache-tomcat-10.0.4 tomcat_dev
   27  cd tomcat_dev/
   28  apt update && default-jdk
   29  apt update && apt install default-jdk
   30  ks
   31  ls
   32  nano server.xml
   33  ls -lah
   34  cd conf/
   35  ls -lah
   36  nano server.xml
   37  clear
   38  ls -la
   39  nano tomcat-users.xml
   40  ls -la
   41  cd ..
   42  ls -la
   43  cd bin
   44  ls -la
   45  chmod +x ./*
   46  ls -la
   47  ./ startup.sh
   48  ./startup.sh
   49  curl localhost:8090
   50  history
