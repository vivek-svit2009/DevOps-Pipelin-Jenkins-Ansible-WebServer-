# DevOps-Pipelin-Jenkins-Ansible-WebServer-

1. Create 3 Diff Server for (Jenkins, Ansible & Web Server)
2. Access All the server's with SSH
3. Update All the Machines (run 'yum update')
4. Log As root user
   1. 'sudo su'
   2. 'passwd root'
   3. For Password less Authentication with another server's (run 
        1. 'ssh-keygen'
        2. 'ssh-copy-id root@desination-PVT-ip'
        3. 'nano /etc/ssh/sshd_config'
        4. 'systemctl restart sshd'
5. Install Java on Jenkins Machine (run 'yum install java* -y') Refer for Java 8 https://stackoverflow.com/questions/24588742/java-8-application-on-ec2
    1. Install Jenkins on same machine. Refer https://pkg.jenkins.io/redhat/
    2. Start Jenkins run 'systemctl start jenkins'
    3. Access Jenkins through public ip address
6. Install Ansible on Ansible server (run 'yum install ansible')
7. Follow 3rd step of 4th point.
8. Install httpd on web-server (run 'yum install httpd')
9. Start httpd run 'systemctl start httpd'
10. Follow 3rd step of 4th point.
11. Go to Dir /var/www/html
    
    To Be Continue.....
