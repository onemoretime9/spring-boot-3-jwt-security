1. Build springboot project
mvn clean package

2. Build docker image
docker build --tag=springboot-jwt:latest .

3. Let’s run our Spring Boot application and PostgreSQL with Docker Compose:
docker-compose up --build

4. If we want to stop all containers, we need to press [Ctrl-C] first. Then we can stop Docker Compose:
docker-compose down