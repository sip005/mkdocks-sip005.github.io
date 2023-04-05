#### 1. Why we use the docker " " command?


-it is short for --interactive + --tty. When you docker run with this command it takes you straight inside the container.

-d is short for --detach, which means you just run the container and then detach from it. Essentially, you run container in the background.

So, if you run the Docker container with -itd, it runs both the -it options and detaches you from the container. As a result, your container will still be running in the background even without any default app to run.


#### 2. What kind of Artitecture does docker use?


Docker uses a client-server architecture. The Docker client talks to the docker daemon, 


#### 3. What are the main underlaying technologies of Docker?


Docker is written in Go and takes advantage of several features of kernel to deliver the functionality. 


#### 4. Describe namespaces in Docker?


Docker uses a technology called namespaces to provide the isolated workspace called container 
