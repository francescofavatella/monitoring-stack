## promtheus
### Docker
https://prometheus.io/docs/prometheus/latest/installation/
http://localhost:9090

### Docker compose
https://docs.docker.com/compose/gettingstarted/

docker-compose up

## grafana
https://grafana.com/docs/grafana/latest/installation/docker/

http://localhost:3000
admin/admin

## springboot
https://spring.io/guides/gs/actuator-service/
https://spring.io/guides/gs/spring-boot-docker/

./gradlew clean build && java -jar build/libs/demo-0.0.1-SNAPSHOT.jar
mkdir -p build/dependency && (cd build/dependency; jar -xf ../libs/*.jar)

curl localhost:8080
{"timestamp":"2020-12-25T17:21:30.311+00:00","status":404,"error":"Not Found","message":"","path":"/"}%

curl localhost:8080
Hello Docker World%

sudo lsof -i tcp:8080
