# SCA-Cloud-School-Application
She Code Africa Cloud School Application

Excericise 1:

* Test process
==============
- Installed docker
- Created app/index.html, Dockerfile
- Built a custom nginx image using the following command
    docker build -t webserver
- Run the webserver in a container 
    docker run -dp 8000:80 --name web webserver
- Checked the webiste output by going to the browser:  localhost:8000 
- Output: Welcome to SCA Cloud School Application