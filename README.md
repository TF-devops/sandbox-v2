# sandbox-v2 with ansible-scripts
1. Create vms for Kubernetes master and node with centos 7 os

2. Generate ssh key for user using below command
    
         ssh-keygen -t rsa 
          
         ssh-copy-id root@<kubernetes-master-ip and kubernetes-node-ip>         

3. Change the ip address in the host file of master and node.

4. login to vms and add the hosts names of master and nodes in all vms and use dns 

        ex. ssh root@x.x.x.x
             
            vi /etc/hosts
            
            x.x.x.x master.example.com
            x.x.x.x node.example.com
