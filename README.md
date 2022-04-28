create an .env file in the root of this project and insert the following 
variables:

* #MongoDB
* MONGODB_USERNAME=user
* MONGODB_PASSWORD=user
* 
* #PostgreSQL
* POSTGRES_USER=postgres
* POSTGRES_PASSWORD=postgres
* POSTGRES_DB=files_info
* 
* #SpringMail
* SPRING_MAIL_PASSWORD=qWERTY2017!
* SPRING_MAIL_USERNAME=shakhno2022@gmail.com

To up the application in a docker container, you need to run the command
docker-compose up --build from the project root