
1. Build a docker image of your project using below command
   docker build -t docker-test .
   Note: docker-test is the name of the image which will get created.

2. After the above process is completed, run below command to check for the image.
	dokcer image ls

3. Now, docker run the image 
	docker run -p 8080:8081 -it  docker-test

4. Through the web browser, test the app.

NOTE: Start the app from the docker.

1.  After the image is created, run the docker using cmd
	docker run -it -p 8080:8081 docker-test /bin/sh
2. At this moment, You will be in  the docker and so, start the app
	./main
3. Test the app using any  web browser
