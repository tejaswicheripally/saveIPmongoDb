mkdir onMyPC
docker run -p 27017:27017 -dit --name mongodb -v onMyPC:/data/db mongo:latest

go get go.mongodb.org/mongo-driver/mongo
go get go.mongodb.org/mongo-driver/mongo/options