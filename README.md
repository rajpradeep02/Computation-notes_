<h1 align = "center">Everything at once</h1> 

## computation
  1. Host: host is any hardware device that has capablity of permitting access to a network via a user interface, specialised software, network address, protocol stacks or any other means. eg, baremetals
  2. VMs: virtual machines:
      - Type 1: it runs directly on baremetals, eg. kvm
      - Type 2: it runs on the top of a OS. vm ware, virtualbox
  3. Container: it is a class or a data structure whos instances are collection of other objects, in other words A container is a sandboxed process running on a host machine that is isolated from all other processes running on that host machine. That isolation leverages kernel namespaces and cgroups, features that have been in Linux for a long time. Docker makes these capabilities approachable and easy to use. To summarize, a container:.
      - docker : its an open platform for developing shiping and running applications
      - orchestrator (managed service) : is the automated configuring coordinating and managing of computer system and software.
    
## Storage:
  1. Objects: an object can be a variable, a data structure, funcitons or a method. Ex :
       - S3: S3 is an object storage service provided by AWS most commonly used, we  make buckets to store data.
  2. Block: a LEXICAL (related to words) structure of sourse code which is grouped together, EX:
       - ECS: it is a fully manages container orchestration service that supports docker container and allowes you to easily run application on a managed cluster.
       - Bucket: it is a container for objects.
## Network:
  1. Load balancer: serves as a single point of contact for clients, or it divert the incoming traffic to many services so that the application runs faster.
       - L7: load balancing allows the load balancer to root a requst based on information in the request itself such as what kind of content is being requested.
           - Layer 7 refers to the outermost seventh layer of the Open Systems Interconnect (OSI) Model. This highest layer, also known as the application layer, supports end-user applications and processes.
       - ![](https://avinetworks.wpengine.com/wp-content/uploads/2021/01/layer-7-osi-model-diagram.png?_t=1611372299)
          
       - L4: Load balancer operate at the transport layer and focus on network layer information like IP address and port numbers.
           - Layer 4 of the OSI model, also known as the transport layer, manages network traffic between hosts and end systems to ensure complete data transfers. Transport-layer protocols such as TCP, UDP, DCCP, and SCTP are used to control the volume of data, where it is sent, and at what rate.
            - Network Load Balancer: A Network Load Balancer functions at the fourth layer of the Open Systems Interconnection (OSI) model. It can handle millions of requests per second. After the load balancer                 receives a connection request, it selects a target from the target group for the default rule.
            - Application Load Balancer: An Application Load Balancer functions at the application layer, the seventh layer of the Open Systems Interconnection (OSI) model.
         - ![](https://d34smkdb128qfi.cloudfront.net/images/kemptechnologieslibraries/about/picture1.png?sfvrsn=453f0d1f_1)
  2. Proxy and Reverse Proxy: A reverse Proxy is a server that sits in front of one or more web servers, intersepting request from clients. This is different from a forward proxy where the proxy sits in front of       the client.
  3. NAT: stands for netword address translation, its the way to map multiple Private Address inside a local netword to a public ip address before transfering the information onto the internet.
  4. Routing: routing enables us to defingn a URL pattern that maps the request handler.
  5. Root 53: It connect user requst to internet application running on AWS or on premices.
       - DNS:  Domain Name System Translate human readable domain names to machines readable IP address.
       - TCP/UDP (L4): TCP  is a connection based protocole while UDP (user datagram protocol) is connection less protocole. 
# Computation-notes_
