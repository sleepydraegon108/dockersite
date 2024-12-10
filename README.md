This project shows how to host a simple static website using Docker and Nginx.

What you need before starting:

    Docker must be installed on your computer.

How to build the Docker image:

Go to the project folder and run this command:

docker build -t static-website .

How to run the Docker container?

Run this command:

docker run -d -p 8080:80 static-website

How to view the website:

Open your web browser and go to:

http://localhost:8080
