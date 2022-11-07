# Milestone-1
The Steps which i have followed for the Installation and Login for CVAT are:
Step 1: Installed the WSL2
Step 2: Downloaded and installed the docker desktop for windows.
Step 3: Downloaded and installed the git for windows.
Step 4: Cloned CVAT source code from the GitHub repository using command:
        git clone https://github.com/opencv/cvat
        and then : cd cvat
Step 5:Run docker containers:
    docker-compose up -d
Step 6: Create super user :
    winpty docker exec -it cvat_server bash -ic 'python3 ~/manage.py createsuperuser'
    
And finally go to localhost:8080
Login with credentials created by the user.
