#DOCKER COMMANDS

1. See Images
>> docker images

2. Build image
>> docker build -t hello-docker:1.0.0 .

3. See history of image
>> docker image history 75e      ==>  ID  75e... 

4. Build container with refresh and without destroy the current container
>> docker run --name my-container -p 8080:80 hello-docker:1.0.0

5. List, Stop and start container
>> docker ps -a
>> docker stop bee              ==>     bee = 3 firs letters of the container ID
>> docker start bee

6. Remove a container
>> docker rm bee
>> docker ps -a

7. Remove an image
>> docker rmi 75e
>> docker images