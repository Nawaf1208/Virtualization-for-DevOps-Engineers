# Virtualization-for-DevOps-Engineers

![VirtualBox](https://img.shields.io/badge/virtualbox-%23183A61.svg?style=for-the-badge&logo=virtualbox&logoColor=white)

![](Virtualization.png)

<details>
<summary><b><i>1.What is Virtualization?</i></b></summary>

$\color{green}{\text{Answer}}$

Virtualization uses software to create an abstraction layer over computer hardware, that allows the hardware elements of a single computer - processors, memory, storage and more - to be divided into multiple virtual computers, commonly called virtual machines (VMs).

</details>

<details>
<summary><b><i>2.What is a hypervisor?</i></b></summary>

$\color{green}{\text{Answer}}$

A hypervisor is software that creates and runs virtual machines (VMs). A hypervisor, sometimes called a virtual machine monitor (VMM), isolates the hypervisor operating system and resources from the virtual machines and enables the creation and management of those VMs.

</details>

<details>
<summary><b><i>3.What types of hypervisors are there?</i></b></summary>

$\color{green}{\text{Answer}}$

Hosted hypervisors and bare-metal hypervisors.

</details>

<details>
<summary><b><i>4.What are the advantages and disadvantges of bare-metal hypervisor over a hosted hypervisor?</i></b></summary>

$\color{green}{\text{Answer}}$

Due to having its own drivers and a direct access to hardware components, a baremetal hypervisor will often have better performances along with stability and scalability.

On the other hand, there will probably be some limitation regarding loading (any) drivers so a hosted hypervisor will usually benefit from having a better hardware compatibility.

</details>

<details>
<summary><b><i>5.What types of virtualization are there?</i></b></summary>

$\color{green}{\text{Answer}}$

Operating system virtualization Network functions virtualization Desktop virtualization

</details>

<details>
<summary><b><i>6.Is containerization is a type of Virtualization?</i></b></summary>

$\color{green}{\text{Answer}}$

Yes, it's a operating-system-level virtualization, where the kernel is shared and allows to use multiple isolated user-spaces instances.

</details>

<details>
<summary><b><i>7.How the introduction of virtual machines changed the industry and the way applications were deployed?</i></b></summary>

$\color{green}{\text{Answer}}$

The introduction of virtual machines allowed companies to deploy multiple business applications on the same hardware, while each application is separated from each other in secured way, where each is running on its own separate operating system.

</details>

## Virtual Machines

<details>
<summary><b><i>8.Do we need virtual machines in the age of containers? Are they still relevant?</i></b></summary>

$\color{green}{\text{Answer}}$

Yes, virtual machines are still relevant even in the age of containers. While containers provide a lightweight and portable alternative to virtual machines, they do have certain limitations.

Virtual machines still matter because they offer isolation and security, can run different operating systems, and are good for legacy apps. Containers limitations for example are sharing the host kernel.

</details>
