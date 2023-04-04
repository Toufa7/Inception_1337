# Inception

## Comparison of virtual machines versus containers


<p align="center" /p>
<img src="https://blogs.sap.com/wp-content/uploads/2018/06/Container_vs_VM.png" width="700">


## Kernel 

The kernel is a core component of an operating system and serves as the main interface between the computer’s physical hardware and the processes running on it. The kernel enables multiple applications to share hardware resources by providing access to CPU, memory, disk I/O, and networking.

Imagine a computer as comprising a series of layers, with the innermost layer being the hardware, and the outermost layers being the software applications running on the computer. In this analogy, the kernel is positioned between the hardware and the applications because it’s not only responsible for managing the hardware’s resources and executing software programs, but also for overseeing the interactions between these layers.

Modern computers divide memory into kernel space and user space. User space is where application software is executed, while the kernel space is dedicated to the behind-the-scenes work needed to run a computer, like memory allocation and process management. Because of this separation of kernel and user spaces, the work done by the kernel isn’t typically visible to the user.