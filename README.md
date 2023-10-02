# movies
This is a back-end project using SpringBoot and mongo-db to create the tables. The GET and POST requests were implemented with Postman(example GET localhost:8080/api/v1/movies, example POST: localhost:8080/api/v1/reviews and inside u can write something with this format{
    "reviewBody": "" , 
    "imdbId": ""
}.).
You will alse need to create a mongo database, and in a .env file(hidden for my safety) type something of this format: 
MONGO_DATABASE=" "
MONGO_USER=" "
MONGO_PASSWORD=" "
MONGO_CLUSTER=" ".

After setting up and running the app, open a browser with link localhost:8080. This project can be used to implement your own front-end project.

