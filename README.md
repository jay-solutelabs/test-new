# Hello_World_NodeJS
NodeJS hello world containerized using Dockerfile

# To run app.js

node app.js

To check hit this url http://127.0.0.1:3000/ from your browser

# To run inside docker container first build the image

docker build -t helloworld:v1 -f Dockerfile .

and then run the image

docker run -it -p 3000:3000 helloworld:v1

To check hit this url http://127.0.0.1:3000/ from your browser
