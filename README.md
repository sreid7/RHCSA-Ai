# RHCSA-Ai
Lab Training for the RHCSA Exam

**DRILL #1: Create and delete users and groups**

sudo useradd -m -c "user1 is a office 2 engineer" -s /bin/bash user1 
sudo passwd user1 
sudo groupadd group1
sudo usermod -aG group1 user1
sudo userdel -r user1
sudo groupdel group1
