# important-commands_devops

transfer files from local to ec2:

SCP: Secure Copy

command: 

     scp -i pemfilename.pem ./files/to/copy username@public-ip:/path/where/you want/to/copy

     for eg: to copy files from local to home directory of ubuntu:
     
     scp -i pemfilename.pem ./portfoliopage  ubuntu@ec2-3-7-68-94.ap-south-1.compute.amazonaws.com:/home/ubuntu
