mvn clean install

docker build --tag=docker-java-hello-world-app .

docker run -p 81:8080 -d docker-java-hello-world-app

http://localhost:80/docker-java-app/test

