***INTRODUCTION***

Operating system - A layer of software
	- job: to provide user programs with better, simpler, cleaner, model of the computer and to handle managing all the resources 
	- runs on bare hardware and provides the base for all the other software 
	- what : software that runs in kernel mode(sometimes?)
	- *function 1*: providing application programmers a clean abstract set of resources instead of the messy hardware ones 
	- *function 2*: managing these hardware resources 

examples of Operating systems
- Windows, Linux, FreeBSD, OS X

Shell - the program that users interact with; text based 

GUI (Graphical User Interface "gooey") - the program that users interact with; icon based;  not a part of the operating system(uses the operating system to get work done)


layers
____________________________________________
Software - 
	user mode - includes the user interface programs 
		user interface programs (Shell, GUI)
			- lowest level of user mode software 
			- allows user to start other programs (web browser, email reader, music player)
	kernel(supervisor) mode - where the operating system runs 
		- has complete access to all the hardware 
		- can execute any instruction the machine is capable of executing 

____________________________________________
hardware - chips, boards, disks, kayboard, moniter
____________________________________________


***1.1.1 THE OPERATING SYSTEM AS AN EXTENDED MACHINE***
Top down
	- OS primaraly provides abstractions to application programs 
	- OS job 2: create a good abstraction aand then implement and manage the abstract objects created
	- OS job 3: hide the hardware and present problems with nice clean elegant consistant abstractions to work with instead


architecture - (included: instruction set, memory organization, I/O, bus structure)
- instead of dealing with a specific hard disk and understanding all the components you would use a software called a disk driver

Disk Driver - (abstraction tool for hard disks) deals with the hardware and provides an interface to read and write disk blocks without getting into the details 

Files - (abstraction tool for Disk Drivers) users can create, write and read files without having to deal with the messy details of how the hardware actually works 



***1.1.2 THE OPERATING SYSTEM AS A RESOURCE MANAGER***
Bottom up 
	- The operating system is there to manage all the peices of a complex system
	- OS Job 2: to provide for an orderly and controlled allocation of the processor, memories, and I/O devices among the various programs wanting them
	- OS primary task: keep track of which programs are using which resource, to grant resource requests, to account for usage, and to mediate conflicting requests from different programs and users 

	OS allows multiple programs to be in the memory ansd run at the same time 

	multiplexing : (a step in resource manangement) Sharing resources in two different ways : time and space 
	ex. resource is time multiplexed: different programs or users take turns using it ex.2 how CPU is distributed 
	ex. resource it space multiplexed: each one gets a part of the resource ex. main memory being spit up between multiple applications at the same time ex.2 the disk


***1.2 HISTORY OF OPERATING SYSTEMS***

	The first digital computer 
		designed by English mathematician Charles Babbage (1792 - 1871)
		did not have an operating system - technology was not there 

		Babbage hired Ada Lovelace as the world's first programmer 

**1.2.1 THE FIRST GENERATION (1945 - 55): VACUUM TUBES**
WWII Period
- John Atanasoff and his graduate student Clifford Berry 
	- built the first functioning digital computer at Iowa State University.
	-  It used 300 vacuum tubes
- Konrad Zuse in Berlin 
	- built Z3 computer out of electromechanical relay
- 1944 
	- Colossus 
		- built and programmed by a group of scientists (including Alan Turing) at Bletchley Park, England
	- the Mark I  
		- built by Howard Aiken at Harvard
	- ENIAC 
		- built by William Mauchley and his graduate student J. Presper Eckert at the University of Pennsylvania.
	- all very primative and took seconds to perform simple calculations
	- written in machine langauge or by wired circuits
	- 20,000ish vacuum tubes
	- problems were strightforward mathematical and numerical calculations
- 1950's
	- introduction of punch cards : write programs on cards and read them instead of using plugboards


**1.2.2 THE SECOND GENERATION (1955 - 65): TRANSISTORS AND BATCH SYSTEMS**

- page 8 to 15

**1.2.4 THE FOURTH GENERATION (1980 - PRESENT): PERSONAL COMPUTERS**
- page 15 - 19 

**1.2.5 THE FIFTH GENERATION (1990 - Present): Mobile computers**
- PDA(Personal Digital Assistant
- Symbian OS - operating system of choice for popular brands like Samsung, Sony Ericsson, Motorola, Nokia
- RIM's Blackberry OSS
- Iphone released in 2007




















