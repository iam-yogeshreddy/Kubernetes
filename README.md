𝐖𝐡𝐚𝐭 𝐢𝐬 𝐜𝐨𝐧𝐭𝐚𝐢𝐧𝐞𝐫 𝐨𝐫𝐜𝐡𝐞𝐬𝐭𝐫𝐚𝐭𝐢𝐨𝐧 :

Container orchestration is the process of automating the management of containerized applications. It involves: 
provisioning, deploying, scaling, securing, networking, integrating, and organizing.

𝙒𝙝𝙮 𝙩𝙝𝙚 𝙘𝙤𝙣𝙩𝙖𝙞𝙣𝙚𝙧 𝙣𝙚𝙚𝙙 𝙩𝙤 𝙗𝙚 𝙤𝙧𝙘𝙝𝙚𝙨𝙩𝙧𝙖𝙩𝙚𝙙 :

Container orchestration is necessary to manage the lifecycle of containers, which can become complex when running in production. Container orchestration automates many tasks, such as deployment, scaling, and networking, which can help with: 

Scalability :
Container orchestration allows you to scale up or down based on workload requirements. 


Security :
Container orchestration helps you manage security policies across platforms and reduce human error. 


Cost :

Containers use fewer resources than virtual machines, which can reduce infrastructure and overhead costs. 


Availability :

Container orchestration can detect issues and automatically work around them to maintain high availability. 


Portability :

Containers are portable, so you can move applications between cloud providers or device types without changing code. 


Updates :

Container orchestration allows you to roll out new versions of an application across a cluster, which can reduce downtime. 


Performance :

Container orchestration can monitor performance and automatically reconfigure containers for optimal performance.


𝑾𝒉𝒚 𝑲𝒖𝒃𝒆𝒓𝒏𝒆𝒕𝒆𝒔 : 

Kubernetes is a container orchestration solution platform which is enterprise ready platform in production.And gives solution to the four main container problems ;


𝗣𝗿𝗼𝗯𝗹𝗲𝗺𝘀 𝘄𝗶𝘁𝗵 𝗱𝗼𝗰𝗸𝗲𝗿 : 

1. 𝑺𝒊𝒏𝒈𝒍𝒆 𝑯𝒐𝒔𝒕 𝑴𝒂𝒄𝒉𝒊𝒏𝒆 :

In Docker Containers are Ephemeral in nature.If one container is consuming more memory with this somewhere the 99th container may not works properly or stops running.

𝑺𝒐𝒍𝒖𝒕𝒊𝒐𝒏 𝒘𝒊𝒕𝒉 𝑲𝒖𝒃𝒆𝒓𝒏𝒆𝒕𝒆𝒔 :

-> Kubernetes cluster contains nodes which is a multiple node architecture,if one container in node is effecting with another container immediately kubernetes will put this container in another node.   


2. 𝑨𝒖𝒕𝒐 𝑯𝒆𝒂𝒍𝒊𝒏𝒈 :

In docker if container downs,our application will not accessible and in this time we have to manually check the status of that container and we have to manually fix that issue.

𝑺𝒐𝒍𝒖𝒕𝒊𝒐𝒏 𝒘𝒊𝒕𝒉 𝑲𝒖𝒃𝒆𝒓𝒏𝒆𝒕𝒆𝒔 : 

-> Kubernetes provides auto healing feature whenever container in pod going down before container goes down kubernetes will creates a new pod and starts that container. Kubernetes in maximum times it can control the damage and fix the damage with auto healing feature. 

4. 𝑨𝒖𝒕𝒐 𝑺𝒄𝒂𝒍𝒊𝒏𝒈 :

In docker setting up a Docker Swarm with auto-clustering and auto-scaling capabilities is a powerful way to manage and scale containerized applications efficiently.But compared to kubernetes docker has less deployment speed.

𝑺𝒐𝒍𝒖𝒕𝒊𝒐𝒏 𝒘𝒊𝒕𝒉 𝑲𝒖𝒃𝒆𝒓𝒏𝒆𝒕𝒆𝒔 :

-> Kubernetes has Replica Set where we can increase our replica's to our expected requirement in yaml file which is a manual way.

-> Kubernetes provides Horizantal Pod Scaler feature which is used means whenever the load reaaching threshold of 80 % in container,HPA will just spin up the container automatically continuosly based on requirement or demand.

6. 𝑬𝒏𝒕𝒆𝒓𝒑𝒓𝒊𝒔𝒆 𝑳𝒆𝒗𝒆𝒍 𝑺𝒖𝒑𝒑𝒐𝒓𝒕 :

-> Docker by default not provides enterprise level support which includes Load Balancer, Auto Scaling, Auto Healing, API Gateway, Firewall etc are very important problems which are overcomes by kubernetes.
