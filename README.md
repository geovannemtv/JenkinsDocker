# Jenkins

## Como rodar
docker build . -t jenkins
docker run -d --name jenkins -p 80:8080 -p 50000:50000 -v <volume-local>:/var/jenkins-home -v /var/run/docker.sock:/var/run/docker.sock jenkins
