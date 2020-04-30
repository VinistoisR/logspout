# logspout
Logspout stack for docker swarm

Deploy this on a docker swarm cluster.  

Provide env var 

$PAPERTRAILPORT

according to your listener in papertrail. 

One container will run on each node and will forward logs for all containers to papertrail. 
