
**Creating and Managing Recipes**

How do you add a new recipe in Yocto?

How do you include a custom recipe in the root filesystem?

How do you create a new directory and install a file using Yocto?

How do you add a new task in a Yocto recipe?

What is the difference between a class (.bbclass) and a recipe (.bb) in Yocto?

Working with Layers and Machine Support

How do you add a new meta layer in Yocto, and what command is used for this?

How do you add a BSP (Board Support Package) layer in Yocto?

In which layer is machine support typically added in Yocto?

Have you ever added support for a new machine in a Yocto layer?

**Configuration and Build Environment**

What are the differences between local.conf and bblayers.conf in Yocto?

What does the MACHINE variable represent in Yocto, and how is it used?

What is the DISTRO_FEATURES variable in Yocto, and how does it affect the build?

Where are the images generated during a Yocto build stored?

**Package Management and Patching**

How do you apply patches to third-party packages in Yocto?

What is the purpose of a .bbappend file in Yocto, and how is it used?

How can you modify an existing recipe from the Poky or OpenEmbedded layer using your own layer (e.g., meta-test)?

What is the difference between DEPENDS and RDEPENDS in Yocto recipes?

What does the SRC_URI variable represent in a Yocto recipe?

**Fetching Sources and Building**

What are the steps to fetch source code from a remote repository in Yocto?

How do you build and install an individual package in Yocto?

How do you build the Linux kernel using BitBake in Yocto?

How do you create a defconfig using BitBake in Yocto?

How do you create a kernel configuration fragment using BitBake in Yocto?

**Development Tools**

Have you used devtool in Yocto? What is its purpose, and how do you create a patch using it?

Have you built an SDK using Yocto? What is the command to build the SDK?

**Board Bring-Up & Boot Process**

What is the process of board bring-up?

Can you explain the Linux ARM boot process?

How do you add new board support packages in U-Boot and the Linux kernel?

How can you modify boot arguments in U-Boot from the command line?

How do you permanently change boot arguments in U-Boot?

How does U-Boot load the kernel and device tree?

What boot arguments does U-Boot need to pass to the kernel to ensure it boots correctly?

What is the command to load images from an MMC device in U-Boot?

How do you configure a boot delay in U-Boot?

What challenges have you faced during board bring-up?

How do you create the default kernel configuration for a new board?

**Device Tree & Kernel Drivers**

What is a device tree, and why is it used?

Can I use network boot to boot the device? If so, how?

How do you add a new device to the device tree?

What is a compatible string in a DTS node?

How do you enable or disable a device in a DTS node?

What information can be passed in a device tree?

How do device and driver bindings happen in the Linux kernel?

How is the probe() function of a driver called?

What is typically done inside the probe() function?

How is memory allocated to a driver? What are kmalloc and vmalloc?

How is an interrupt handler registered in the kernel?

How is an interrupt handled by the processor?

What are the top half and bottom half in interrupt handling?

What is the difference between softirq and tasklet?

**Concurrency & Synchronization**

What is a race condition?

How can race conditions be avoided?

What are the different synchronization mechanisms available in Linux?

What is a spinlock?

Can a spinlock be used in an interrupt handler?

Can we sleep in an interrupt handler?

What is a deadlock, and how can it be avoided?

What is context switching?

What is preemption?

What is SMP (Symmetric Multiprocessing), and how does it work on a single-core CPU?

What is the difference between synchronous and asynchronous operations?

**Secure Boot & Optimization**

What is Secure Boot, and what are the steps to implement it?

What is PKI (Public Key Infrastructure)? What is a private key?

How did you optimize boot time? Please explain in detail.

How did you optimize memory usage?

If a single application consumes 50% of memory and 30–40% of CPU, how can it be optimized?

Do you know what jitter is?

How do you improve overall system performance?

**Device Driver Development**

Can you write a skeleton character driver?

How do you insert a driver module into the kernel?

What is the difference between insmod and modprobe?

What are major and minor numbers in device drivers?

Can two devices have the same major and minor numbers?

How do you debug a kernel module that causes a system crash or kernel panic?

What are the differences between static and dynamic module loading? How do you manage module dependencies?
