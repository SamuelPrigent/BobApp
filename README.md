# BobApp

Clone project:

> git clone XXXXX

## Front-end

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start;

### Docker Front

Build the container:

> docker build -t bobapp-front .

Start the container:

> docker run -p 5600:80 --name bobapp-front -d bobapp-front

## Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

> mvn spring-boot:run

Launch the tests:

> mvn test

### Docker Back

Build the container:

> docker build -t bobapp-back .

Start the container:

> docker run -p 8081:8080 --name bobapp-back -d bobapp-back
