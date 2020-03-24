# sandbox-v2 with ansible-scripts
1. Create Kubernetes master and node vms with centos 7 os

2. Generate ssh key for user using below command
    
         ssh-keygen -t rsa 
          
         ssh-copy-id root@<kubernetes-master-ip and kubernetes-node-ip>         

3. Change the ip address in the host file of master and node
