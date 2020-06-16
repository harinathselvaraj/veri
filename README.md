# veri

```
Instructions to Run the Project - 

Step 1: Download the Docker Image from Github Repo - 
docker pull docker.pkg.github.com/harinathselvaraj/veri/harinath_docker_img:1.0

Step 2: Start the Docker container from the Downloaded Docker Image - 
docker run -p 8888:8888 docker.pkg.github.com/harinathselvaraj/veri/harinath_docker_img:1.0

Step 3: Optional Step (If you wanted to view the Jupyter Notebook code)
Copy and paste the url shown in the terminal in a new browser tab. It should look like the one below, 
http://127.0.0.1:8888/?token=542839b0048e58134ae0ff5940887c3b4a1a0e86c9b7c3c9

Step 4: Command to view the ID of running container
docker ps -a

Step 5: Enter in to container to execute the python script - 
docker exec -ti --user root 74f33052ef5a bash
cd work
python payout.py

Note: Replace '74f33052ef5a' to the container ID obtained from step 4

```
