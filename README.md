# EXPERIMENT 01 ALP on fundamental arithmetic and logical operations using 8086
## Name : SANTHOSH D
## Roll no : 212223220099
## Date of experiment : 19-08-2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations

## Components required: 8086  emulator 

## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition alp
```
org 100h
mov ax,2345H
mov bx,1111H
ADD ax,bx 
ret
```

## Output  
 <img width="1944" height="1080" alt="add" src="https://github.com/user-attachments/assets/fa64f880-bde9-49ab-9551-fcf7684369fe" />

## Subtraction alp
```
org 100h
mov ax,2345H
mov bx,1111H
SUB ax,bx 
ret
```
 
## Output  
<img width="1944" height="1080" alt="sub" src="https://github.com/user-attachments/assets/265c0980-f002-4219-ad0b-155c7e70cad1" />

## Multiplication alp 
```
org 100h
mov ax,2345H
mov bx,1111H
mul ax
ret
```

 ## Output  
<img width="1918" height="1080" alt="image" src="https://github.com/user-attachments/assets/0c35a2a0-4b03-49f6-bced-82e657f645dd" />

## Division alp 
```
org 100h
mov ax,2345H
mov bx,1111H
div bx 
ret
```

## Output 
<img width="1944" height="1080" alt="div" src="https://github.com/user-attachments/assets/5c2e12dd-b48a-450d-9599-fffa36640e7c" />

## Programs for logical  operations

## AND alp
```
org 100h
mov ax,2345H
mov bx,1111H
AND ax,bx 
ret
```

## Output
<img width="1944" height="1080" alt="add" src="https://github.com/user-attachments/assets/303f6d7d-fd8f-43b1-a567-37c74d586773" />

## OR alp
```
org 100h
mov ax,2345H
mov bx,1111H
OR ax,bx 
ret
```

## Output
<img width="1944" height="1080" alt="OR" src="https://github.com/user-attachments/assets/58b5b59e-015a-4d41-b6d5-2436f206400e" />

## XOR alp
```
org 100h
mov ax,2345H
mov bx,1111H
XOR ax,bx 
ret
```

## Output
<img width="1944" height="1080" alt="XOR" src="https://github.com/user-attachments/assets/dad5b8be-ddd4-4f63-8d0c-e83463fbcc97" />

## NOT alp
```
org 100h
mov ax,2345H
NOT ax
ret
```

## Output
<img width="1944" height="1066" alt="not" src="https://github.com/user-attachments/assets/39f9e968-d343-4ce4-b626-5f2f7eb02148" />


## Result :
 
The execution of ALP on fundemental arithmetic and logical operations executed successfully.







