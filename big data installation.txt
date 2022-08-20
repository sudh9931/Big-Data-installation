
Downlaod cloudera
https://drive.google.com/file/d/1WzYxDmaRnJUpAGhZcdl8WXlyc6NClDUe/view?usp=sharing

Download VM 

https://www.virtualbox.org/wiki/Downloads


Putty Downlaod

https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html


File Zilla dowonload

https://filezilla-project.org/download.php?platform=win64

FOR MAC 

Hi, for mac m1, try to go with below lsited steps.
Go on to your terminal                  
1. docker ps - To list running docker containers
2. docker pull cloudera/quickstart:latest - To pull docker image from repository
3. docker run --hostname=quickstart.cloudera --privileged=true -t -i -v ~/Documents/dockersrc:/Src --publish-all=true -p 8888 cloudera/quickstart /usr/bin/docker-quickstart - To start cloudera docker container



https://medium.com/@rakeshgopidi/installing-cloudera-quickstart-vm-through-docker-hub-on-mac-m1-879f4a3d0fd4
