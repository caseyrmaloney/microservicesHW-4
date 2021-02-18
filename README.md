# Homework #4

What type of machine does my service run on? 
There are three options. 
  1. Physical Machine 
  2. Virtual Machine 
  3. Containers 


They all have dfferent performances, resource efficient, and idolation. 


***Physcial Machines*** is one that we are more known to. Its our traditonal computer with CPU, and its subsystems: memory, disk, network. 
Physical machines are controlled by the operating system and the hardware systems. 
But why do we need _virtual machines_ or _containers_?




### What is a Virtual Machines?

Virtual machines are created when a physical machine is divided to run a seprated operating system for each process. They cannot access the resources that a physical machine provide. 
Reason why virtaul machines are used: 
  - organizaional 
  - logistical 

***Organizational***, is used to allow multiple teamss of one company use the same physical machines. They allow each team to have their own vitrual machine.
***Logistical***, is used to allow servies and upgrades to be done on different schedules for different services. 


### Advantages of Virtual Machines 

Virutal machines can make computing more efficent. Since most applications today do not need use all of the resources that a phycial machine provide, vitual machines help reduce the size for the right needs. This is called _stranded capacity_. This also allows better isolations between other applications. They won't effect each other when one has a problem. They are ***fast*** to create and destory. Vitrual machines are sometimes called short-lived machine. They are created for a specific task and then deleted when finsihed. Since these machines are ran through the software, that also makes them ***programmable***. Meaning that they can be modidyied, started, and stoped. Some vitural machines can also be moved between physical machines. This occurs when one physcial machine needs to be upgraded or repaired. 


### What is a Container? 


A container is a group of processes running on an operating system that are isolated from other processes. Each contain its own space that includes a name, network configruation, and other resources. They consume resources at the same level as processes. They are less wasteful than virtual machines and physcial machines. They are controled as a group and have a memory limit. 


### Advantages of Containers


Since containers are memory limited, the group sum of total memory of the processes cannot pass that limit. Like said before they are less ***wasteful***. When you have multiple containers running on one machine you ***cannot have conflicts or dependencies***. It contains its own copy of the libraies and packages to avoid collisions. Containers are ran by the operating system, but they don't use the whole system. They only use the specific files that the container needs. Containers allocate space as needed and run the processes that are only realted to the software.


### Why Use Physical Machines over Vitrual Machines?

There are some disadvantages to using vitrual machines. They allocate a fix amount of space, and typically allocate a large chunk of RAM and disk. They share resources, like the CPU. Sometimes the vitrual machines can be working and using all of the CPUs cores and faulter the CPU. Making it run slower. They run a full operating system which take up alot of memory and space. They keep the allocated memory even if it is not being used. Downfall to this is that this memory space cannot be reallocated to somewhere where it is needed. Typically physical machines are more predictable and reliable. 



### Cloud computing with Microsevices
Cloud Native not only allows you to sign up and use it with your existing program, it also affects the design, implemenatation, deployment, and operating your application. Now how can we ultilze cloud computing? We can use _containers_ for that. Package your software with everything you need to execute it into one executble package. It allows the containers to be ***independent*** of the enviroment and make it highly portable. It allows you to add and remove instances of the application. Containers contain everything that you need. Containers are ***built as a system of microservices***. We can implement a system of multiple smaller applications. What are the benefits of this? 


  1. Functionality
      - Everything working together allows fast and easy access. It's easier to understand smaller applications that          have one functionality. This speeds up development and it's easier to adapt.
  2. Scaling is more efficient 
      - Containers are used to allow efficiently. Starting another container to handles the increase of user requests.         This is called _horizontal scaling_. 
  3. Cheaper 
      - It's cheaper to scale a system of microservice. 


Overall with microsrvice, it allows for an better use of cloud resources and its cheaper. It provides a new way to structure your system, and helps with the complexity. 






