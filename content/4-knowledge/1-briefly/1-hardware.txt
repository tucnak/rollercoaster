# Hardware

This book is all about software and code, but I'd love to make sure that you understand trivial concepts of computer hardware first. I'll do my best to make it super concise. In fact, this particular chapter might be interesting to any geek sort of a person, since it covers nothing, but some generic computer architecture reference.

### CPU
Central Processing Unit is the heart of any computer that performs all the actual computation. You can't even imagine how good it is at math, mate. Intel Core i7 875K (2011) processor carries approx 92,1·10<sup>10</sup> (92.100 millions) instructions per second at 2.93 GHz, which is hell a lot. But what does it all mean?

First of all, let's understand the way CPU works. Modern processors are super-dooper complicated, but let's simplify it a little bit. What it basically does is simple binary math: you ask it to process two bits of data with some operation and it gives you a resulting bit back. For instance, there is an OR operation, which returns 1 if any of the bits given is 1 and returns 0 otherwise:
```
1 || 1 = 1
0 || 0 = 0
1 || 0 = 1
0 || 1 = 1
```

Obviously, modern processors go far beyond the binary math. They are also capable of moving memory in RAM and reading/saving information from the storage, but you get the whole idea. Processor is all about doing primitive operations.

A single processor is built of multiple **cores**. Each core performs in parallel to others. Quad core processor is able to perform form operations at the same time, making it two times quicker than an identical double core processor. Making use of multiple cores is crucial and a little bit complicated, yet we'll run some parallel code in the following sections.

Now let's talk about **frequency** (aka clock rate). In order to understand what chip frequency clock rate is, you'd rather need some background in electromechanics, which you might not have. That's the main reason why I wouldn't like to come up with definitions like: *The clock rate of a CPU is normally determined by the frequency of an oscillator crystal, producing a fixed sine wave—the frequency reference signal*. Just think of frequency as of determining factor of speed. Higher frequency — faster it performs instructions. Don't lose the point here: CPUs with higher frequencies are not better than others, but the same processor performing on higher rate is. What really matters is processor's unique architecture. I'd bet that a processor of 2015, running on 1 GHz (gigahertz, one billion oscillations per second) would beat a processor back from 2007, running on 2 GHz.

### RAM
Random-access memory is a form of computer data storage. A random-access memory device allows data items to be accessed (read or written) in almost the same amount of time irrespective of the physical location of data inside the memory. In contrast, with other direct-access data storage media such as hard disks, CDs and the older [drum memory](https://en.wikipedia.org/wiki/Drum_memory), the time required to read and write data items varies significantly depending on their physical locations on the recording medium, due to mechanical limitations such as media rotation speeds and arm movement delays.

Once your computer is started, its operating system and all the startup software is loaded into RAM. Every time you start an application, it gets loaded into RAM. You lose all the data on RAM disk when the computer is shut down, unless memory is arranged to have a standby battery source, so you can't use it as persistent data storage.

### Storage
I've got a funky feeling that you know what storage is already, so I won't tell you obvious things. I still can't mention a difference between different kinds of storage devices: HDD and SSD. HDD stands for `hard disk drive` and SSD stands for `solid-state drive`. While HDD stores information using one or more rigid ("hard") rapidly rotating disks (platters) coated with magnetic material, SSD uses integrated circuit assemblies as memory.

Since SSDs has no moving (mechanical) components, they are much faster and reliable. SSDs are typically more resistant to physical shock, run silently, have lower access time, and less latency. However, while the price of SSDs has continued to decline over time, consumer-grade SSDs are still roughly six to seven times more expensive per unit of storage than consumer-grade HDDs.

### Peripheral
A peripheral (or I/O device) is a "device that is used to put information into or get information out of the computer". There are two different types of peripherals: input devices, which interact with or send data to the computer (mouse, keyboards, etc.), and output devices, which provide output to the user from the computer (monitors, printers, etc.). Some peripherals, such as touch screens, can be used both as input and output devices.
