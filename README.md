# Project Description
Part 3: This part will test your understanding of Docker volumes and how to use them in Docker containers. You will be required to perform several tasks and document your  findings in a README.md file on your GitHub repository.

# NGINX
### This section shows the working flow of `nginx` image.  
1. First I pulled the nginx image from docker hub using the command `docker pull nginx`.  
2. Then I mount the image as shown in the picture below.  
![Nginx image mount](/assets/nginx_volume_mount.png)
3. Below is default output of nginx image shown when nginx container is running.  
![Nginx image mount](/assets/nginx%20welcome.png)
4. The picture below shows the nginx copy command, showing the copy of the file from host directory to container directory.
![Nginx image mount](/assets/nginx_copy.png)
5. Now, the custom output is shown.  
![Nginx image mount](/assets/nginx_custom_output.png)

# HTTPD
### This section shows the working flow of `https` image.  
1. First I pulled the httpd image from docker hub using the command `docker pull httpd`.  
![Nginx image mount](/assets/httpd_pull.png)
2. Then I mount the image as shown in the picture below.  
![Nginx image mount](/assets/httpd_mount.png)
3. Custome output of httpd image shown when httpd container is running.  
![Nginx image mount](/assets/httpd_output.png.png)
4. The picture below shows the httpd copy command, showing the copy of the file from host directory to container directory.
![Nginx image mount](/assets/filecopyproof_httpd.png)
5. Now, at the end, the picture below shows the cleaning of the volume mounted.    
![Nginx image mount](/assets/clean_volum.png)