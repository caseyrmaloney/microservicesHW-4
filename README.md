# Homework #4

What type of machine does my service run on? 
There are three options. 
  1. Physical Machine 
  2. Virtual Machine 
  3. Containers 


They all have dfferent performances, resource efficient, and idolation. 


***Physcial Machines*** is one that we are more known to. Its our traditonal computer with CPU, and its subsystems: memory, disk, network. 
Physical machines are controlled by the operating system and the hardware systems. 
But why do we need _virtual machines- or _containers_?




### What is a Virtual Machines?

Virtual machines are created when a physical machine is divided to run a seprated operating system for each process. They cannot access the resources that a physical machine provide. 
Reason why virtaul machines are used: 
  - organizaional 
  - logistical 

***Organizational***, is used to allow multiple temas of one company use the same physical machines. They allow each team to have their own vitrual machine.
***Logistical***, is used to allow servies and upgrades to be done on different schedules for different services. 


### Advantages of Virtual Machines 

Virutal machines can make computing more efficent. Since most applications today do not need use all of the resources that a phycial machine provide, vitual machines help reduce the size for the right needs. This is called _stranded capacity_. This also allows better isolations between other applications. They won't effect eachother when one has a problem. They are ***fast*** to create and destory. Vitrual machines are sometimes called short-lived machine. They are created for a specific task and then deleted when finsihed. Since these machines are ran through the software, that also makes them ***programmable***. Meaning that they can be modidyied, started, and stoped. Some vitural machines can also be moved between physical machines. This occurs when one physcial machine needs to be upgraded or repaired. 


### What is a Container? 


A container is a group of processes running on an operating system that are isolated from other processes. Each contain its own space that includes a name, network configruation, and other resources. They cnsume resources at the same level as processes. They are less wasteful than virtual machines and physcial machines. They are controled as a group and have a memory limit. 


### Advantages of Containers


Since containers are memory limited, the group sum of total memory of the processes cannot pass that limit. Like said before they are less ***wasteful***. When you can multiple containers running on one machine you ***cannot have conflicts or dependencies***. It contains its own copy of the libraies and packages to avoid collisions. Containers are ran by the operating system, but they are dont use the whoe system. They only use the specific files that the container needs. Containers allocate space as needed and run the processes that are only realted to the software.


### Why Use Physical Machines over Vitrual Machines?

There are some disadvantages to using vitrual machines. They allocate a fix amount of space, and typically allocate a large chunk of RAM and disk. They share resources, like the CPU. Sometimes the vitrual machines can be workign and using all of the CPUs cores and faulter the CPU. Making it run slower. They run a full operating system which take up alot of memory and space. They keep the allocated memory even if it is not being used. Downfall to this is that this memory space cannot be reallocated to somewhere where it is needed. tyoically phsycail machines are more predictable and reliable. 



### Cloud computing with Microsevices








