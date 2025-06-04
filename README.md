# EXPERIMENT--01-ALP-FOR-8086
Name : Kurapati Vishnu Vardhan Reddy <br>
Roll no : 212223040103 <br>
Date of experiment : 12-03-2025





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

## Addition  of 8 bit ALP

```assembly
org 100h

mov ax,100h
mov bx,200h
add ax,bx

ret
```

## Output  
![image](https://github.com/user-attachments/assets/999c02dc-1178-4285-94cf-f012088b09f9)
 
## Subtraction of 8 bit numbers  ALP 
```assembly
org 100h

mov ax,100h
mov bx,200h
sub ax,bx

ret
```

## Output  
![image](https://github.com/user-attachments/assets/8e06697c-6f26-4c7e-87b0-cf17565651a1)

## Multiplication alp 
```assembly
org 100h

mov al,88h
mov bl,77h
mul bl

ret
```
## Output  
![image](https://github.com/user-attachments/assets/d931a4fa-5742-41a7-9e9e-2be066978458)

## Division alp 
```assembly
org 100h

mov al,88h
mov bl,77h
div bl

ret
```

## Output  
![image](https://github.com/user-attachments/assets/3ff7759a-d902-4d91-b295-d2be4ba28f3e)

## AND alp
```assembly
org 100h

mov al,25h
mov bl,50h
and al,bl

ret
```

## Output  
![image](https://github.com/user-attachments/assets/36a44efe-aac4-4cfe-944b-4149d304b312)


## OR alp 
```assembly
org 100h

mov al,90h
mov bl,65h,
or al,bl

ret
```
## Output  
![image](https://github.com/user-attachments/assets/b6465cd1-6a23-438b-beeb-fad16cd3ad24)

## NOT alp 
```assembly
org 100h

mov al,90h
not al

ret
```
## Output 
![image](https://github.com/user-attachments/assets/2764f4f0-8e87-408d-8b2e-bc95e2ed4a9e)


## XOR alp 
```assembly
org 100h

mov al,90h
mov bl,90h
xor al,bl

ret
```
## Output  
![image](https://github.com/user-attachments/assets/93816a4c-ae5c-40bc-a75a-3ccb4319bf6f)



## Result :
Thus, we have have written and executed alp on fundamental arithmetic (add,sub,mul,div) and logical operations (and,or,not,xor) successfully







