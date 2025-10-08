# test-api

docker build -t titanic-service:latest .

docker run -d --name titanic-service -p 50:5000 titanic-service:latest