Polecenie do tworzenia obrazu:

docker build --build-arg BASE_VERSION=19.8.1 -f Dockerfile_lab5 -t sprlab5:v1 .

Polecenie uruchamiające kontener:

docker run -d -p 8084:8080 --name zlab5v5 sprlab5:v1

Sprawdzenie czy healthcheck działa:

docker ps