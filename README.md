# Project Description
Part 1: Docker file Creation, GitHub and Docker Hub Integration

# Commands Used

## Git
`git init`: This command initializes a project directory with git VCS.  
`git add`: This command pushes the changes to staging area.  
`git commit`: This command commit the changes held in staging area.   
`git remote -v`: We use this command to know the remote location added in the git.  
`git remote set-url origin <url>`: We set remote repository using this command.  
`git push --set-upstream origin main`: This command sets the shortcut for remote origin. So, next time the developer can only use the `git push` command rather than the long command to push changes to the remote library.  

## Docker
`docker ps`: This command shows the docker containers running.  
`docker build -t <image_name>:tag .`: We use this command to build an image by providing image name and tag.   
`docker images`: Shows the list of images available in the docker.  
`docker run -d -p host_port:container_port <image_name>`: Use to run the image provided in <image_name> by setting the host and container ports to access the app from outside the container.  
`docker tag <image_name>:tage_if_any DOCKER-USER-NAME/<repo_name>`: We use this command to push local docker image to docker hub repository of a user.  
`docker push DOCKER-USER-NAME/<repo_name>`: After the above command, this command pushes the image to user's (i.e., mwaheedkhan/node-app) repository.  