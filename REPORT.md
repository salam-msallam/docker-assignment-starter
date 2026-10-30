# My Docker Assignment Report

Name: _Salam Msallam__

Repository URL: https://github.com/salam-msallam/docker-assignment-starter 

Use short sentences. Add the answers requested in the assignment PDF.
Keep passwords, tokens, and private keys out of this report.

## Mission 1 - First Container

What happened:
I used the Nginx image to run a web server in a container named web-server. I accessed it using http://localhost:8080 on my Ubuntu VM. 

What I learned:
8080:80 maps port 8080 on the host to port 80 inside the container. 


## Mission 2 - Build Your Own Image

What happened:
I created a Dockerfile for the Node.js application using FROM, WORKDIR, COPY, RUN, EXPOSE, and CMD.
The first build failed while downloading the node:22-alpine base image. After retrying the download, Docker successfully pulled the base image.
I then continued with the application build and the message.txt experiment. 

What I learned:
Rebuilding the image and recreating the container is needed to include the edited file when it was copied at build time. 

Problem I faced:
 The download of node:22-alpine was extremely slow and failed with connection reset by peer. 
I also ran docker build once without the final . build-context argument.

## Mission 3 - Broken Port

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________

## Mission 4 - Environment Variables

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________

## Mission 5 - Docker Hub

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________

## Mission 6 - Remote Deployment

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________

## Mission 7 - Volumes

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________

## Mission 8 - Docker Networking

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________

## Mission 9 - Docker Compose

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________

## Bonus Mission

Commands used:

____________________

What happened:

____________________

What I learned:

____________________

Problem I faced:

____________________

How I fixed it:

____________________
