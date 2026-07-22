---
title: Hardware & Software Manual
---

# Hardware & Software Manual

One of the biggest challenges facing newcomers to technology is understanding where hardware ends, software begins, and firmware fits into the equation.

These three concepts form the foundation of nearly every piece of modern technology.

Whether you're troubleshooting a computer, configuring a network, building a Raspberry Pi project, securing a server, or simply trying to understand why something broke, understanding the relationship between hardware, software, and firmware is essential.

This manual documents the concepts, tools, and lessons I've learned throughout my journey in technology.

## The Three-Layer Model

When I explain computers to beginners, I often think of technology as three interconnected layers:

1. Hardware
2. Firmware
3. Software

Each layer performs a different function, but all three must work together.

## Hardware

Hardware refers to the physical components of a device.

If you can physically hold it, touch it, connect it, replace it, or break it, it's probably hardware.

Examples include:

- CPUs
- Memory (RAM)
- Motherboards
- Hard drives
- SSDs
- Monitors
- Keyboards
- Mice
- Network switches
- Cameras
- Printers

Hardware provides the physical foundation that makes computing possible.

Without hardware, software has nowhere to run.

### Common Hardware Components

#### Central Processing Unit (CPU)

The CPU is often described as the brain of the computer.

Its primary role is executing instructions and performing calculations.

Most computing tasks eventually pass through the CPU.

#### Memory (RAM)

RAM provides temporary working space for running applications.

More RAM generally allows:

- Better multitasking
- Larger workloads
- Improved responsiveness

Unlike storage, RAM is cleared when power is removed.

#### Storage

Storage devices retain information even after power is turned off.

Examples include:

- Solid State Drives (SSDs)
- Hard Disk Drives (HDDs)
- USB drives
- SD cards

Storage contains:

- Operating systems
- Programs
- Files
- User data

#### Motherboard

The motherboard connects all major components together.

It serves as the communication backbone of the system.

#### Graphics Processing Unit (GPU)

GPUs specialize in visual processing and parallel workloads.

Traditionally associated with gaming, modern GPUs are also heavily used for:

- Artificial intelligence
- Video processing
- Scientific computing
- 3D rendering

## Firmware

Firmware occupies the space between hardware and software.

Many people hear the word but never fully understand what it means.

Firmware is specialized software permanently or semi-permanently stored on hardware devices.

Its purpose is to provide low-level control of hardware components.

Examples include:

- BIOS
- UEFI
- Router firmware
- Camera firmware
- SSD firmware
- Printer firmware

Without firmware, much of the hardware would not know how to function.

### BIOS and UEFI

When a computer powers on, firmware executes before Windows or Linux ever loads.

This startup firmware:

- Initializes hardware
- Performs hardware checks
- Locates boot devices
- Starts the operating system

Historically this was known as BIOS.

Modern systems typically use UEFI.

### Updating Firmware

Firmware updates can:

- Improve stability
- Fix bugs
- Improve security
- Add new features

However, firmware updates should be approached carefully.

A failed firmware update can render a device temporarily or permanently unusable.

## Software

Software consists of the instructions that tell hardware what to do.

Unlike hardware, software is intangible.

It exists as data and code.

Examples include:

- Windows
- Linux
- Microsoft Office
- Google Chrome
- Video games
- Antivirus software

Hardware performs the work.

Software tells the hardware what work to perform.

### Operating Systems

The operating system serves as the bridge between users and the underlying hardware.

Examples include:

- Windows
- Linux
- macOS
- Android
- iOS

The operating system manages:

- Memory
- Storage
- Devices
- Applications
- Security

### Applications

Applications perform specific tasks for users.

Examples include:

- Word processors
- Web browsers
- Media players
- Accounting software
- Security tools

Applications rely on the operating system to interact with hardware.

## How Hardware, Firmware, and Software Work Together

A useful example is a security camera.

### Hardware

The camera itself contains:

- Sensors
- Processors
- Network interfaces
- Storage

### Firmware

The camera's internal firmware:

- Controls operation
- Manages settings
- Handles networking
- Processes video streams

### Software

Viewing software allows users to:

- Monitor feeds
- Configure recording
- Receive alerts
- Review footage

If any layer fails, the system may stop functioning properly.

## Drivers

Drivers often confuse newcomers because they blur the line between hardware and software.

Drivers are specialized software that allows operating systems to communicate with hardware.

Examples include:

- Printer drivers
- Video drivers
- Network drivers
- Audio drivers

Without the proper driver, hardware may not function correctly even when physically healthy.

## Common Troubleshooting Approach

When diagnosing technology problems, I often ask:

### Is It Hardware?

Questions might include:

- Is the component receiving power?
- Are there visible failures?
- Is the device recognized?

### Is It Firmware?

Questions might include:

- Is the device using current firmware?
- Has a recent update caused problems?
- Are settings configured properly?

### Is It Software?

Questions might include:

- Is the application configured correctly?
- Are drivers installed?
- Is the operating system functioning normally?

Breaking problems into these categories often makes troubleshooting significantly easier.

## Tools I've Found Valuable

### Microsoft Windows

Nearly every professional environment I've worked in has relied heavily on Windows systems.

Understanding Windows remains one of the most valuable skills for technology professionals.

### Linux

Linux powers an enormous portion of the modern technology world.

Many:

- Servers
- Security tools
- Embedded systems
- Networking devices

depend on Linux in some form.

### Raspberry Pi

Raspberry Pi devices offer one of the most affordable ways to learn:

- Linux
- Networking
- Automation
- Programming
- Hardware integration

Several of my personal projects began with Raspberry Pi devices.

### GitHub

GitHub became particularly valuable while building The Mully Manual.

It introduced me to:

- Version control
- Documentation
- Website hosting
- Source management

## Lessons Learned

### Technology Is Just Layers

Much of technology appears complicated because people try to learn everything at once.

Breaking systems into:

- Hardware
- Firmware
- Software

makes many problems easier to understand.

### Fundamentals Matter

Products change.

Concepts remain.

Understanding the fundamentals usually matters more than memorizing specific products.

### Troubleshooting Beats Memorization

The best technology professionals are not the people who have all the answers.

They are the people who know how to find answers when they don't.

## The OSI Model

If I had to identify one concept that helped me understand networking more than any other, it would be the OSI Model.

The Open Systems Interconnection (OSI) Model provides a framework for understanding how information travels from one device to another.

At first glance the model can seem overly academic.

In reality, it is one of the most useful troubleshooting tools available.

The OSI Model breaks network communication into seven layers.

Each layer performs a specific job and communicates with the layers above and below it.

Rather than viewing a network as one giant system, the OSI Model allows us to isolate problems and examine them one layer at a time.

### Layer 7 - Application

The Application Layer is where users interact with network services.

Examples include:

- Web browsers
- Email clients
- Teams
- Discord
- Streaming applications

This is typically the layer users see.

### Layer 6 - Presentation

The Presentation Layer focuses on formatting and translating data.

Functions may include:

- Encryption
- Compression
- Character encoding

This layer ensures information is understandable to both systems.

### Layer 5 - Session

The Session Layer manages communication sessions between devices.

Responsibilities include:

- Session establishment
- Maintenance
- Termination

Think of this layer as managing conversations.

### Layer 4 - Transport

The Transport Layer is responsible for reliable data delivery.

The two protocols most commonly associated with this layer are:

#### TCP

Transmission Control Protocol provides:

- Reliability
- Error checking
- Ordered delivery

TCP is commonly used for:

- Websites
- Email
- File transfers

#### UDP

User Datagram Protocol prioritizes speed over reliability.

Common uses include:

- Gaming
- Streaming
- Voice communications

### Layer 3 - Network

The Network Layer handles logical addressing and routing.

The primary protocol is:

- IP (Internet Protocol)

This layer determines how traffic moves between networks.

Routers primarily operate here.

### Layer 2 - Data Link

The Data Link Layer handles communication between devices on the same network segment.

Functions include:

- MAC addressing
- Frame creation
- Error detection

Switches primarily operate at this layer.

### Layer 1 - Physical

The Physical Layer consists of the actual hardware moving data.

Examples include:

- Copper cables
- Fiber optic cables
- Wireless signals
- Connectors
- Network interface hardware

If a cable is unplugged, the problem exists here.

### Why The OSI Model Matters

The OSI Model shines during troubleshooting.

For example:

Internet isn't working.

Rather than randomly guessing, we can work through the layers.

Questions might include:

Layer 1:
Is the cable connected?

Layer 2:
Does the switch see the device?

Layer 3:
Does the device have an IP address?

Layer 4:
Can traffic reach the destination?

Layer 7:
Is the application functioning properly?

Using the model systematically often reveals the problem much faster than trial and error.

### A Practical Example

Imagine opening a web page.

When you type a URL into your browser:

- Layer 7 processes the web request.
- Layer 4 creates the TCP connection.
- Layer 3 identifies where packets must travel.
- Layer 2 prepares frames for transmission.
- Layer 1 sends signals across physical media.

The receiving device performs the same process in reverse.

Every website visit, every email, every online game, and every streaming video relies on these same principles.

### Why I Think The OSI Model Is Important

Many technology concepts become easier to understand once viewed through the OSI Model.

Networking.

Cybersecurity.

Cloud computing.

System administration.

All of them build upon the same fundamental communication process.

Whenever I encounter a network problem, I still find myself thinking through the layers.

It remains one of the most valuable mental models I've learned throughout my career.

## RFID & NFC Implants

One of the more unusual pieces of technology I own isn't in my pocket.

It's in my hand.

I have an NFC/RFID implant located between my thumb and index finger. The implant functions similarly to an NFC card, key fob, or access badge, allowing me to store and transmit small amounts of information when scanned by compatible devices.

While implants remain a niche technology, they demonstrate an interesting intersection between hardware, software, and human-computer interaction.

### What Is NFC?

Near Field Communication (NFC) is a short-range wireless communication standard.

Many modern devices include NFC capabilities, including:

- Smartphones
- Payment terminals
- Access control systems
- Smart locks
- Security badges

Communication occurs only when devices are extremely close together.

### How I Use Mine

My implant serves several purposes.

#### The Mully Manual

One of the simplest uses is storing the URL for The Mully Manual.

With a compatible smartphone, I can quickly open the website simply by scanning the implant.

#### Access Control

The implant can also function similarly to a key fob for compatible applications and systems.

Depending on the device and configuration, NFC implants may be used for:

- Access badges
- Smart locks
- Authentication
- Automation tasks

### Lessons Learned

Most people's reaction is one of curiosity.

They either think the technology is incredibly futuristic or completely unnecessary.

The truth is somewhere in the middle.

The implant doesn't provide any superpowers, but it does serve as an interesting demonstration of how technology can become integrated into everyday life.

More than anything, it has become a conversation starter and a fun technology project.

### Philosophy

Technology doesn't always have to solve a major problem.

Sometimes it's okay to build, test, and experiment simply because something is interesting.

The implant represents curiosity more than practicality, and curiosity has been responsible for many of the technological advances we take for granted today.

## Philosophy

Technology can seem overwhelming when viewed as thousands of separate devices, applications, and systems.

In reality, most technology is built upon a relatively small number of foundational concepts.

Once you understand how hardware, firmware, and software interact, the rest becomes much easier to learn.

The goal of this manual is not to catalog every piece of technology available.

The goal is to explain the foundational concepts that make modern technology work.
