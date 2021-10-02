# **Types of Virtualization**

Course: DevOps

Mod: Week 1

Topic: Types of Virtualization

Amount of time: 1.5 hours

Author: Thomas Fowler

## **Lesson Objectives**

* Describe the different types of virtualization.

* List and describe the use cases for each type
of virtualization.

* Understand the tradeoffs and benefits of each
virtualization type.

--------------------------------------------

## **Virtualization Types**

### **Server**

When we discuss virtualization, typically what that means is
the virtualization of a server. This server represents what
would normally be a physical server and is managed by the
host system's hypervisor. Like a physical server, a
virtualized server hosts applications and services from
various application teams. These applications and services
are managed like any other on the virtualized server's guest
operating system.

--------------------------------------------

### **Client & Desktop**

Client and desktop virtulization is the virtualization of a
guest operating system for the purposes of providing an end-user
workstation environment. These virtualized workstations or
desktops provide the means to provision an environment for users
to perform their day-to-day tasks using typical productivity
software and/or development tools.

This scenario is typical of large organizations where managing
large swaths of devices for every employee is very
time-consuming and cost-prohibitive. Further, provisioning,
patching, securing, and finally delivering machines to employees
takes a significant amount of time. Virtualization of the user's
workstation provides a quicker and cheaper way to deliver the
tools the user needs to perform the function of their role.

Some obvious tradeoffs between physical and virtual workstations
are performance, ability to customize the environment, and the
necessity of network connectivity for virtualized environments.

--------------------------------------------

### **Services & Applications**

In addition to physical servers and workstations, services and
applications are also virtualized. With applications, the
applications are virtualized in a way where they are delivered
directly to the user without any need for a visual or desktop
environment from the guest operating system. This allows for
further isolation and restriction of applications in use by
employees and prevents any additional or unwanted activity on
the guest operating system.

Virtualized services behave in a similar manner, where the
service is virtualized on the guest operating system without
any additional supporting software or other tools one finds
in a typical operating system. The service runs on the guest
operating system as if it were on a physical or virtualized
server.

--------------------------------------------

### **Networks and Network Devices**

Networks between virtual machines, etc. can also be
virtualized. Multiple subents can be created on a physical
network through combined networking devices (e.g. routers,
switches, etc.) This practice can lead to independent channels
of bandwidth that can later be assigned to virtual devices
on the virtual network. Additional benefits to this include
increased network speed and more efficient usage of bandwidth,
network reliability, and better monitoring and security.

--------------------------------------------

### **Storage**

Storage can be virtualized by consolidating multiple physical
storage devices to appear as a single storage device. Benefits
include increased performance and speed, load balancing and
reduced costs. Storage virtualization also helps with disaster
recovery planning, as virtual storage data can be duplicated
and quickly transferred to another location, reducing downtime.
