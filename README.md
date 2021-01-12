# SCA Cloud School Application

### Deployment instruction
======================

**Prerequisite**: make sure you have installed docker
1. Pull the image from dockerhub repository

    URL: https://hub.docker.com/r/bezu/sca-cloud
    <code>docker pull bezu/sca-cloud</code>
2. Run it in a container

   <code>docker run -dp 8000:80 bezu/sca-cloud </code>
3. To check the output, go to:<code> localhost:8000 </code>, and you shoud see the text: 

    Welcome to SCA Cloud School Application , this is my first assessment

    OR
- You can skip step 1 and go directly to step 2: the run command, and docker will pull the image from docker hub and run a container.
