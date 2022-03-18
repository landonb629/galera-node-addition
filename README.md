# galera-node-addition

Purpose: playboook will install necessary components needed for mysql galera. 

##IN CURRENT STATE, THERE IS MANUAL ORCHESTRATION NEEDED##

how to use: 

- edit galera nodes config, add new host IP in the gcomm:// string 
- edit the server.cnf file in github, you will have to add a new IP address, hostname, and copy the gcomm:// string 
- deploy the playbook 
- on master node, bootstrap the cluster 
- start maria DB service on new node
