Chapter 1 Operating Systems 

- Modern computer consists of 
	- lots of hardware
		- one or more processor
		- main memory 
		- Disk 
		- Printers
		- A keyboard
		- A mouse
		- Displays
		- Network Interfaces
		- Various other Input/ output devices

- The applications you see on your computer has been developed by a person 
- developer = application programmer 
- Application programmer perspectives 

- you dont worry about how the conversion takes place you just worry about developing the code
	- you dont have to worrry about the hardware level programming becasue of the opersting system 

	- operating system takes care of how the applications compunicate to the hardware

	-MANAGING.... these resources and managing them 


	Software - Operating system --> (User mode and kernel mode) 
		-User mode
			- Application: Web browser, Email reader, Music player, Visual studio code 
				- do not have access to the hardware
			- User interface program: Terminal, GUI (graphical user interface)(double clicking on an icon and it opens),  windows:command prompt, shell, 
				- helps run other applications n your computer 
				- makes use of operating system so it can use the hardware
				- lower level user mode : shell or GUI
		- Kernel mode (aka Supervisor mode)
			- operating system completes all modual operations
			- operating system: has complete access of hardware
			- Rest - Subset of machine instructions 
			

	Hardware - CPU, Memory, Disk


Difference between OS (operating system) and normal S/W (software)  --> hard to draw a clear boundary

Email reader
.c: takes care of the clock interrupt handler 
Some user-mode software helps the operating systems --> change password.

Difference between OS and other software 
- OS is huge, complex, and long-lived 
	- Linux or Windows operating systems have 5 million lines of code. If you include all of the source code libraries, it is 70 million lines of code(Windows) --> not easy to update

	- when updating your phone, you are updating the OS --> to update an OS it is a complex job --> you need to know what all lines of code are doing

	- We will write simulations (write a simulation code for scheduling algorithms) 

What is an Operating system?
- to create an abstraction for a programmer, so they don't have to worry about the hardware 
- act as an intermediate person between the hardware and the user 
- whose job is to provide user programs with a better, simpler, cleaner model of the computer and to handle managing all the resources (BOOK DEFINITION) 

- an extended machine 
	- allows the user to understand where the files are on the computer fully
	- only have to write 'touch nameFile'; you don't have to worry about how the file is being created
	- top-down 
	- Hardware, OS, Application --> abstraction

- a Resource Manager 
	- bottom-up
	- treats the hardware as different resources 
	- Manage hardware devices amaong various programs
	- allowing multiple programs to run at the same time
	- sharing resources - MULTIPLEXING (technology that is able to combine multiple communication signals together in order for them to traverse an otherwise single signal communication medium simultaneously ex. CPU and RAM)
			- CPU and multiple programs that want to run on it 
			- Applications are queued inside the RAM and the CPU will look at the RAM and see where it is needed 
			- CPU returns on applications so it feels as if we are running so many applications but you are really only on the one the CPU is running 
	- Time
		- CPU and multiple programs that want to run on it 
		- printer and multiple print jobs
	- Space
		- CPU and multiple programs that want to run on CPU
		- Single disk and many users 
	- RAM is small compared to the hard disk
	- OS figures out how hardware is shared between applications 

The operating system decides how many resources go to each application (CPU - shared between all the applications)


End of lecture questions:
What are the two main functions of an operating system?


List and explain different types of operating systems.


What is the difference between kernel and user mode? Explain how having two distinct modes aid in designing an operating system.


Instructions related to accessing I/O devices are typically privileged instructions, that is, they can be executed in kernel mode but not in user mode. Give a reason why these instructions are privileged.



























