# important-commands_devops

#transfer files from local to ec2:

SCP: Secure Copy

command: 

     scp -i pemfilename.pem ./files/to/copy username@public-ip:/path/where/you want/to/copy

     for eg: to copy files from local to home directory of ubuntu:
     
     scp -i pemfilename.pem ./portfoliopage  ubuntu@ec2-3-7-68-94.ap-south-1.compute.amazonaws.com:/home/ubuntu


     
#remove commands variation:

command:

     rm -d	Remove an empty directory using the rm command.
     rm -r	Remove a non-empty directory and its content.
     rm -f	Ignore any prompt when deleting a write-protected file.
     rm -rf	Ignore any prompt when deleting a write-protected non-empty folder.
     rm -i	Output a prompt before deleting every file.
