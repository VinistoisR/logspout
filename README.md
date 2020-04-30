# logspout
Logspout stack for docker swarm

Deploy this on a docker swarm cluster.  

Provide env var, eg:

PAPERTRAILURL=logsx.papertrailapp.com:12457

according to your listener setting in papertrail. 

One container will run on each node and will forward logs for all containers to papertrail. 

this stack auto detects x86 and arm64 nodes and deploys compatible containers on each.
