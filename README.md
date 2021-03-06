#  Building a PC
### By Jacob Woratzeck
Building a PC gives you much more control over the specifications and cost of a computer than if you were to purchase a pre-built one from a retailer. This tutorial will focus mainly on purchasing parts for a PC build and will include links to resources for the actual assembly. This tutorial will be focused on building a Windows based machine. I will also be assuming that the PC will be running at stock conditions as overclocking can make PC building much more complicated.

This tutorial is aimed at people who are familiar with PCs and basic computing concepts but have never built their own computer or who might not be familiar with computing hardware. Because of this, the tutorial will only be providing high-level explanations of the hardware as getting more technical can be confusing for first-time PC builders. 

## Contents
### [Gathering Parts](#gathering-parts-1)
* [Getting Started](#getting-started)

* [Case](#case)

* [CPU](#cpu)

* [Motherboard](#motherboard)

* [Video Card](#video-card)

* [RAM](#ram)

* [Storage](#storage)

* [Power Supply Unit](#power-supply-unit)

* [Monitor](#monitor)

* [Peripherals](#peripherals)

### [Assembling the Parts](#assembling-the-parts-1)
### [Installing the Operating System](#installing-the-operating-system-1)
### [Finishing Touches](#finishing-touches-1)

## Gathering Parts
### Getting Started
To get started, I would recommend going to [PC Part Picker](https://pcpartpicker.com/list/). This website will help you browse all of the available hardware and makes it easy to compare different parts. It can help you keep track of all your hardware and ensure that you are not forgetting anything essential. It also helps keep track of the total cost of the build and provides links to where you can actually purchase a part, most often Newegg, a popular technology retailer. The site will also alert you if any of the parts on your list will be incompatible with each other.
### Case
Cases (sometimes called chassis, towers, system units, or cabinets) come in a variety of sizes and shapes and is the first place to start as it can affect what hardware you will be able to fit inside. There are several things to consider when purchasing a case:
1. How much space do you have for the tower?
2. What type of hardware do you want to put into the case?
3. How do you want the PC to look?

Oftentimes, a case will be classified by the size of motherboard it can fit. The most common motherboard sizes include EATX (largest), ATX, micro-ATX, and miniITX (smallest). Other sizes do exist, however, but the majority of cases will be advertised to fit one of these motherboard sizes. Even if a case is designed to fit a larger motherboard, it will often be able to hold a smaller motherboard as well. For example, a case that can fit an ATX motherboard, will likely be able to house a microATX motherboard as well.

Cases can also be referred to by their physical size in a different way. Cases labeled as "small-form-factor" are typically quite small and are usually designed to fit miniITX motherboards. A "desktop" case is often smaller and designed to lay horizontally on a desktop, often so a monitor can sit atop it. Conventional vertical desktop towers are classified in 3 sizes: mini-towers, mid-towers, and full towers. These sizes do not represent exact
measurements, so two mid-sized towers may differ in size.

![Case Comparison](Images/Case-Comparison.jpg)

Airflow is also important to consider when looking at cases because having the hardware inside it overheat can cause damage to the system. To remedy this, fans are typically attached to the case to circulate air in and out of it. Oftentimes, a case will include several fans with it, but if it does not, you will want to pick up a few to protect your system from overheating issues.

To build a relatively powerful machine, having a larger case would likely be the best option since powerful hardware tends to be bulkier and larger in size. I would recommend selecting a case that can fit an ATX motherboard as you will have more space to work with, which is nice when building for the first time.
### CPU
Probably the most important piece of hardware to choose is the Central Processing Unit (CPU). The CPU sends signals to control the other parts of the computer, similar to how a brain controls a body. It is the electronic circuitry within a computer that carries out the instructions of a computer program by performing the basic arithmetic, logic, control, and input/output (I/O) operations specified by the instructions. Your choice of CPU will affect which motherboard you will need to purchase, which in turn affects the other hardware that will be compatible with the system.

Presently, there are two major companies producing CPUs: Intel and AMD. In the past, Intel has dominated the higher-end CPU market, but recently AMD has begun to release products offering strong competition to Intel. Because of this, there are now more options for you to consider than previously.

![CPUs](Images/AMD-Intel-CPU.jpg)

In terms of processing power, there are two main specifications to look at when selecting a CPU: clock speeds and the number of cores. Having higher clock speeds lead to faster processing speeds and higher core counts allow for more computations to be done simultaneously. For things like gaming, having faster clock speeds is typically more important that having higher core counts. For things like video editing or digital modeling, having more cores tends to give a bigger boost to performance than only clock speeds.

Intel's mainstream consumer CPUs are classified by several levels: i3, i5, i7, and the newest, i9. The biggest variation between these tends to be core counts followed by clock speeds with i3s having lower core accounts and i9s having the most. Typically, the more cores a CPU has, the lower the clock speed of each individual core will be, but not always. i7 and i9 CPUs typically have a feature called hyperthreading, which divides a core into two virtual cores that can work simultaneously, improving multi-core workload performance. On the newest generation of Intel CPUs, only the i9 uses hyperthreading. The i7 does not.

AMD’s mainstream CPUs, called the Ryzen series, act in a similar way with Ryzen 3 being comparable to an i3, Ryzen 5 to i5, and Ryzen 7 to i7. It should also be noted that the term "hyperthreading" is exclusive to Intel. AMD has something called Simultaneous Multi-Threading, which is essentially the same.

For general purpose PC usage, an i5 or Ryzen 5 should be sufficient, but for more intensive computing, an i7 or Ryzen 7 will offer the best performance. i3 and Ryzen 3 should only be considered for very basic computing tasks. i9 CPUs are quite expensive and will likely be overkill for the majority of users. To get a better idea of how a CPU will perform, I recommend looking at benchmarks of the CPUs to see how they perform in various real-world situations. I recommend looking at [User Benchmark](https://cpu.userbenchmark.com) as it has a large quantity of benchmarks that you can browse to compare various CPUs based on a number of parameters.

It should be noted that a CPU will require a cooler to properly function. The latest AMD CPUs include a stock cooler with them, but the newer Intel CPUs do not, so you would need to purchase one. For the sake of this tutorial, almost any cooler should be fine, since I am assuming the CPU will be running at stock speeds and overheating should not be an issue. Older generations of Intel CPUs did include a stock cooler, so depending on the CPU you select, you may or may not need to purchase one.
### Motherboard
The motherboard is a very important piece of the computer that holds and allows communication between many of the crucial electronic components of a system, such as the central processing unit (CPU) and memory, and provides connectors for other peripherals.

The CPU you select will determine the motherboard you need to purchase. Intel CPUs and AMD CPUs will not work on the same motherboard because they use different connection ports. Typically, Intel alters the socket of their CPUs with each new generation of CPU released. For example, the most recent line of Intel CPUs, the 9XXX series, uses a different socket than the 7XXX series released in 2017. This means that the two would need different motherboards as they would not fit into the same socket.

AMD has taken a different approach in recent years and has decided to use the same socket type for new CPUs for the next few years. This means that if you want to upgrade your CPU in the near future, you would not need to purchase a new motherboard like you would for an Intel CPU. Current generations of AMD's Ryzen CPU line use the AM4 socket.

After finding a motherboard that your selected CPU will fit into, the next step is to compare the features of the motherboards. Some of the important features to consider include onboard Wi-Fi, Bluetooth, and the amount of USB ports a motherboard has. While virtually all modern motherboards will have an embedded sound card, it is worth double checking because if it does not, you will need to purchase a dedicated sound card.

It is also important to choose a motherboard that is the appropriate size for your goals. As mentioned previously, powerful hardware, especially the video card, tends to be large and bulky, so if you plan on using the PC for intensive activities like video editing or gaming, you should choose a larger motherboard size to allow you to fit bulkier parts into it easier.

![Motherboard Comparison](Images/Motherboard-Comparison.png)

### Video Card

![GPU](Images/GPU.jpeg)

The video card is sometimes referred to as a graphics card or a GPU as it houses the Graphics Processing Unit. The GPU is specialized for display functions and renders images, animations and video for the computer's screen.

Certain motherboards, or even certain CPUs, may have onboard or integrated GPUs, meaning you would potentially not need to purchase one at all. For intensive graphical activities, having a dedicated or discrete GPU is an immense performance boost over an integrated GPU. For gaming, the GPU nearly always will be the main determining factor of performance.

Like with CPUs, there are two major GPU manufacturers: Nvidia and AMD. Nvidia GPUs are vastly more popular and have a much larger share of the market and typically lead the market in terms of performance.

Note that AMD GPUs do NOT have to be used with AMD CPUs. They will also work with Intel CPUs. Likewise, Nvidia GPUs will also work with AMD CPUs.

There are a number of specs to consider when selecting a GPU including clock speeds, memory speed, and bandwidth. As virtually all of the specs are important in varying degrees, it is difficult to decide which will perform the best on paper. Because of this, I recommend looking at benchmarks of various GPUs and deciding which one will meet your needs and then compare their prices. The prices of video cards vary widely with the newest flagship models being around $1200 and older models being less than $100. Benchmarks for various cards will give you a better idea of how the card will perform in a real world situation.

Similar to looking at benchmarks for CPUs, [User Benchmark](https://gpu.userbenchmark.com) is an excellent resource for looking at benchmarks and comparing things like performance and cost for GPUs.

### RAM

![RAM](Images/RAM-Stick.jpg)

Random Access Memory (RAM), sometimes simply referred to as "memory", is another critical piece of computer hardware. RAM temporarily stores data, serving as the computer's "working" memory. Additional RAM allows a computer to work with more information at the same time, which usually has a dramatic effect on total system performance.

Virtually all modern computers use RAM called Double Data Rate Synchronous Dynamic Random Access Memory (DDR SDRAM). There are several variations of DDR SDRAM on the market currently. The most recent iteration of DDR SDRAM is called DDR4 SDRAM. DDR3 SDRAM is still relatively common, however. The newer iterations of DDR SDRAM have faster speeds and are more energy efficient. The CPU and motherboard you chose for your build will determine what type of RAM will be compatible with your system (likely either DDR3 or DDR4), so it is important to ensure your chosen RAM will be compatible with your system.

After determining which type of RAM you should purchase, you must determine how much you need. For simple tasks like basic Office document work or web browsing, 4GB of RAM would likely be sufficient but 8GB is fairly standard for most situations. For more intensive activities like gaming, photo/video editing, or heavy multitasking, 16GB would likely be a better choice. The highest-end machines will often have 32GB of RAM or even more, but these are edge cases and this amount is not necessary for most people.
### Storage

![SSD vs HDD](Images/SSD-VS-HDD.jpg)

Storage is an important aspect of the PC as it is what will store both the operating system and all of your programs and documents. There are two major types of storage on the market: Hard Disk Drives (HDD) and Solid State Drives (SSD). HDDs have a disk that physically spins when the computer reads and writes to it. An SSD has no moving parts within it and instead uses integrated circuit assemblies to persistently store data. Because of this, SSDs are much faster than HDDs, but they are also significantly more expensive for the same amount of storage space.

After choosing the type of storage device that is best for you, it is important to select an appropriate size for the device. What you will be using the device for will determine how much storage space you will need. Around 500 GB of storage space is likely to be more than enough for most people.
### Power Supply Unit

![PSU](Images/PSU.jpg)

The final part to choose for the internal components of the PC build is the Power Supply Unit (PSU). This is the part that will deliver electrical power to all of the other internal parts. Because of this, it is important to get a power supply that will be able to sufficiently power all of the parts you have chosen. The GPU and the CPU are the most power intensive parts of a PC. Looking at the required power for these two will give you a good estimate of what wattage power supply you should purchase.

Note: Having a power supply that can provide more power than you need will not hurt the other parts and overestimating your power needs is actually often a good idea.

If you are using PC Part Picker, the site will automatically calculate the estimated wattage your computer will need to be properly powered based on what you have chosen in your parts list.
### Monitor

![Monitor](Images/Monitor.jpg)

It is important not to forget to purchase a monitor as well. There are a wide variety of monitors to choose from with widely varying specs and equally varying price points.

While there are a ton of varying types of monitors, to keep it simple, there are 3 major specifications to consider when looking for a monitor:
1. Resolution
2. Refresh Rate
3. Response Time

Resolution refers to how many pixels there are on the display. The higher the resolution, the more crisp an image will appear. Currently, common monitor resolutions include 1080p (1920x1080), 1440p (2560x1440), and 4K (3840x2160 OR 4096x2160).

The refresh rate refers to the maximum amount of frames the monitor can display each second, referred to as a framerate. Higher framerates will result in smoother movement. Common monitor refresh rates are 30Hz, 60Hz, 75Hz, 120Hz, 144Hz, and 280Hz.

Response time is the amount of time a pixel takes to change, measured in milliseconds. A lower response time leads to less blur around moving objects and less visual artifacts. Common response times are 5ms, 3ms, and 1ms.

When selecting a monitor is important to determine what the system will be used for. For basic tasks like watching videos or web browsing, virtually any monitor will be sufficient. For gaming, where there are large amounts of movement, a higher refresh rate and lower response time will be desirable. A higher resolution is often always more desirable, but the higher the resolution, the more processing power it takes to render all of the pixels. Because of this, it is important to gauge which is more important to you: higher framerates or higher resolutions. For gaming, the framerates will largely be dependent on your graphics card, so looking at benchmarks for the card at various resolutions will help you determine what level of performance you can expect and help you decide which monitor you should purchase.

### Peripherals

![Mouse and Keyboard](Images/Mouse-Keyboard.jpg)

Purchasing peripherals will vary wildly from person to person. The most important things to purchase are a mouse and keyboard. Any will do, but oftentimes people will have personal preferences about these. Speakers are another peripheral to consider, but what you purchase will largely be up to your personal needs and preferences.

## Assembling the Parts
As the parts you have chosen will vary, it is nearly impossible to provide exact instructions for assembling all of your parts. Some things to note, however, are:
1. Ensure you stay grounded by periodically touching something metal (that is not the computer) and avoid any static while working with the parts. Discharging static onto the parts (especially the motherboard) could damage the hardware and prevent it from working.
2. Do not have any power flowing to the system while you are plugging in or unplugging any parts as this could also damage the parts.
3. Once the PC is assembled, do not touch the parts while it is powered on as this could cause a short and ruin the build.
4. Try to keep the cables as organized in the case as possible. Depending on the case, there are likely holes to feed cords into and out of to keep them organized. Dealing with all of the cords is often one of the most challenging parts of building a PC, so the more organized you can be, the easier it will be.
5. If you have decided to purchase a dedicated GPU, the monitor(s) should be plugged into the ports on the GPU and not the motherboard. This will ensure the monitor is receiving its picture from the more powerful GPU instead of from the integrated GPU.

Below I have linked two resources for assembling the PC hardware as they do an excellent job walking through the process and they have been useful to me in the past when building a PC. There is both a text guide (with pictures) and a video guide depending on your preference.

[How to Build Your Own Computer (Text)](https://www.howtogeek.com/howto/uncategorized/building-a-new-computer-part-2-putting-it-together/)

[How to Build a PC in 30 minutes with EasyPCBuilder! (Video)](https://www.youtube.com/watch?v=0bUghCx9iso)

## Installing the Operating System
![Windows 10](Images/Windows-10.jp2)

Once all of the parts have been assembled, it is time to finally boot up the new PC, but before you can do that, you have to install an operating system to the computer for it to be functional. For the sake of simplicity, I will assume you are going to be installing Windows. To do so, you will need to purchase a USB flash drive to hold the operating system for installation. It is possible to use a DVD instead, but a USB flash drive is much more convenient. Note that a CD will not work as it will not have enough storage capacity to store the operating system. You do not need to immediately purchase a Windows license, but the operating system will have a number of restrictions until it is activated with a license key.

Below is a link to Microsoft's support page detailing how to create a Windows Installation USB.

[Create installation media for Windows](https://support.microsoft.com/en-us/help/15088/windows-10-create-installation-media)

After creating the Windows Installation media, plug the Windows Installation USB into one of the USB ports on your motherboard. On first boot, the PC will likely go directly into the BIOS. The layout of the BIOS will vary drastically between motherboards but you should look for a location to set the boot sequence. You will want to set the boot sequence to first go to the Windows Installation USB you have created and plugged in. After setting this, you should search for a location to exit the BIOS. If everything goes correctly, you should be met by a Windows installation screen where you can follow the onscreen directions to install Windows.

Below are some video tutorials for creating the installation media and installing Windows from a USB.

[How to Install Windows 8.1 from USB Guide/Tutorial](https://www.youtube.com/watch?v=NT0KFR09Svc)

[How to Install Windows 10 from a USB Flash Drive](https://www.youtube.com/watch?v=SKbR6XT7fcA)

## Finishing Touches

Once you have successfully installed Windows, you are essentially done! It is a good idea to check for Windows updates to ensure that you are running the most recent version of the operating system. Also important is to update all of the drivers for the components on your PC to ensure everything is working optimally. You can either search the web for drivers for each individual part, or use a driver installation tool to make the process easier. I have linked one such program below. It has a free trial for its premium version, which should be more than sufficient for installing all the drivers to get your system up to date.

[Driver Easy](https://www.drivereasy.com)




