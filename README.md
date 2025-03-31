1. OpenShift is a tool from the company Redhat, it internally uses the
Kubernetes

2. K8s is just a short way of writing Kubernetes. It's a tool used to manage and run apps in containers.

3. Kubernetes is an opensource tool so many of the companies took its code
and after making some changes they redistributed it with their names. For
example:- Redhat’s Openshift, AWS Elastic Kubernetes service, Mirantis
Kubernetes etc

4. Lets first understand the concept of the containers.

5. To launch any idea into the market we need to create an application
or any program for it and for launching or using the program we
need an operating system, there is no way to interact with any
program without an operating system

6. The power of containerization is that it can launch the entire OS in
just less than a second whereas other ways can take up to 1 hour to
do the same

7. For implementing the Containerisation we have different tools that
are known as the container engines like Docker, CRIO, Podman
etc.
8. In containerisation the OS is called as the containers.

9. There are various uses of OS here like building, testing the code,
deploying the code etc

10. In the agile world we are launching the containers on high scale and now
the question arises is who is going to manage all these containers, who
will keep an eye on the containers that they are working fine or not, for
this we need the container management tool because it is impossible for a
human to keep on monitoring all those containers.

11. Container management means if by chance the containers fail or shut
down due to any fault or reasons then we need someone who will monitor
the containers continuously and if any fault comes up, the new container
should be launched instantly.

12. It is very difficult to manage a huge number of containers by a human
being so we need a tool here that will help in monitoring the containers.

13. The management tool we are talking about here is the Kubernetes.

14. Kubernetes is not a container engine, it internally connects with the
docker or any container engine to launch the containers.

15. If any fault happens and due to that the containers are terminated then
Kubernetes will contact to the docker or the container engine and will
launch the exactly same container.

16. n the Kubernetes world the container is known as the pod and launching
the pod is known as the deployment
