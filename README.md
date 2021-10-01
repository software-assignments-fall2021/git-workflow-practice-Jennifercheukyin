# Kubernetes Architecture and Components 

[Kubernetes Fundamentals For Absolute Beginners: Architecture & Components](https://medium.com/the-programmer/kubernetes-fundamentals-for-absolute-beginners-architecture-components-1f7cda8ea536)

[CONTAINERS, KUBERNETES, AND SERVICE MESH IN A NUTSHELL](https://pvillela.com/2021/containers-kubernetes-and-service-mesh-in-a-nutshell/)


To understand what Kubernetes is, one must know about containers. Containers are a virtualization technology 
that enables processes to run in isolation from each other on the same host. Containers are lighter-weight than 
virtual machines and enable more efficient utilization of computing capacity. All containers running on a host 
share the host’s operating system kernel, but each container chooses its own individual libraries and respective 
versions (which need to be compatible with the kernel version). 

Kubernetes is a container orchestration system that lets you deploy, scale, and manage containerized applications. 
Container orchestration is defined as the capability to define, deploy, and operate a compute cluster consisting 
of multiple virtual machines or physical servers to launch containers and manage their lifecycle. Thus, Kubernetes 
is de facto a container orchestration engine. 

What I found interesting about containerization, Kubernetes, and service mesh in general is that it represents a shift away from 
monolithic architecture to isolated microservices. From my previous internships, the utilization of containerization decreases 
dependency on other services and make deployment smoother and frictionless. 