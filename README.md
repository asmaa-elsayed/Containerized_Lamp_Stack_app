# ContainerizedLampStack_app
This is a repo for installing the lampstack app on a docker container

##Setup Environment
1- 2 Ubuntu local machines
2- Install docker and start it on the target machine using ansible
3- Create docker file with base image for lamp stack application and build the image
4- Run the container from the lampstackimage
5- Copy the index.php to the contain (/var/www/html)
6- Expose the container from outside on port 8081
