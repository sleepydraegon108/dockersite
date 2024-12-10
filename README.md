This project shows how to host a simple static website using Docker and Nginx.

What you need before starting:

    Docker must be installed on your computer.

How to build the Docker image?

go to the project folder and run this command:

docker build -t static-website .  #we assemble the docker image with this command (which we specified in our Dockerfile)

To run it locally run:

docker run -d -p 8080:80 static-website

To view the website go to:

http://localhost:8080

Note: other won't see your website unless you publish it somewhere and get a URL (unless you wanna keep your computer ON day and night and run it locally)
