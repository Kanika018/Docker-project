# Docker-1

# Myproject

 Here i have created a project for installation of ghost. Ghost is a free and open source blogging platform written in JavaScript      and mysql as a databse provider.

# Pre-configurations needed:

   I am using RedHat Enterprise Linux. I have also installed docker software.  
   
# Setting up required things:

  - Disabling firewalld: 
     systemctl stop firewalld
  - Starting docker:  
     systemctl start docker 
     
# Images used:

   mysql:5.7
   ghost:latest

# Docker-compose:

   install the docker-compose before you use it.
   you can create and edit this file using 
       vi docker-compose.yml
    
# Docker-compose up-

   As in the picture use (#docker-compose up) to complete the set-up

# Ghost:latest:

  You can browser and type (#localhost:81) and done you will be able to see your ghost.

 # Docker-compose start/stop:

   After using docker-compose up now in one click you can stop your whole setup using -(#docker-compose stop) #to first stop it# -(#docker-compose start) #to start again
  
 # Docker-compose down:
 
   You cam easily stop the containers using (#docker-compose down) command.
   
   
 # THANK YOU  
