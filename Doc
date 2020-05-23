1. I created a Dockerfile for each APP, each one in it's own Directory.
2. I built the image for each app with the following commands:
    - docker build -t avihaiv/devops-ex:app-a .
    - docker build -t avihaiv/devops-ex:app-b .
3. I then ran each image with his own desired port:
    - docker run -p 5000:5000 -d avihaiv/devops-ex:app-a
    - docker run -p 5001:5001 -d avihaiv/devops-ex:app-b
4. Once I was able to see that both images are running locally I stopped both images with:
    - docker stop <DOCKER ID>
5. I pushed both images to my own Docker Hub repository:
    - https://hub.docker.com/r/avihaiv/devops-ex
6. I tried to create a cluster but since I don't have a paid account it was impossible.
7. I pushed all of my files to my repository in GitHub:
    - https://github.com/AvihaiV/devops-ex
8. If I had the resources, I would check the amount of requests, once it reached a certion limit
   that can be checked with API requested, I would create another node and will add it into 
   the LB, that it can now receive requests as well.
9. I would then create a pipeline using Jenkins, to first build the image, then run the image,
   and make sure the image is running with a basic "curl -i" request.
   Once the image is up I would then push a request to build a node out of it and scale up when needed.

--I know this is not much, but giving the situation I believe that if I had the resources I would 
  finish the assignment.

Thank you for the opportunity,
Avihai
