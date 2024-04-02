# EXPERIMENT--01-ALP-FOR-8086




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
```
Name :JAYAKRISHNAN L B L
Roll no : 212222230052

```

## Addition  of 8 bit ALP 

```
org 100h  
MOV AL,02H;
MOV BL,04H;
ADD AL,BL;
MOV [2432h],AL;
ret
```

## Output  
 ![image](https://github.com/Jayakrishnan22003251/EXPERIMENT--01-ALP-FOR-8086/assets/120232371/a6b50c84-64d5-4784-8bfc-18831b8c6014)
 

## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h
MOV Al,05H;
MOV Bl,04H;
SUB Al,Bl;
MOV Cl,Al;
ret
```
## Output  
![image](https://github.com/Jayakrishnan22003251/EXPERIMENT--01-ALP-FOR-8086/assets/120232371/0dd85de9-21d1-476f-97a6-fd24816fd3ae)

## Multiplication alp 
```
org 100h  
MOV CL,00h;
MOV AL,12H;
MOV BL,02H;
MUL BL;
HLT;
```
 ## Output  

![image](https://github.com/Jayakrishnan22003251/EXPERIMENT--01-ALP-FOR-8086/assets/120232371/4e7722ef-fef5-464c-8aa2-0b9868d21c2b)

## Division alp 
```
org 100h  
MOV CL,00h;
MOV AL,40H;
MOV BL,10H;
DIV BL;
RET
```
## Output  
![image](https://github.com/Jayakrishnan22003251/EXPERIMENT--01-ALP-FOR-8086/assets/120232371/214a2b74-aa49-4c40-8691-0ac20248b7c5)


## Result :
 

Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.






