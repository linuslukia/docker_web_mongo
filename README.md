# docker_web_mongo
a project using docker and mongodb

example usage(in ubuntu enviroment)
start container in local:
cd docker_web_mongo
sudo docker-compose up


curl -H "Content-Type: application/json" -X POST "http://0.0.0.0:5000/v1" -d "key=key11&value=value11"
to save (key11,value11)

curl -X GET http://0.0.0.0:5000/v1/key/key11
 to get the value corresponding to key11



close container:
sudo docker-compose down
