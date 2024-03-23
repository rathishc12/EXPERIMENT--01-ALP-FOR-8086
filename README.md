# EXPERIMENT--01-ALP-FOR-8086
```
Name : RATHISH KUMAR C
Roll no : 212222100043


```

## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
## Theory 

Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color
  
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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
```
org 100h

mov ax,8h;
mov bx,7h;
add ax,bx;
mov [2345h],ax;

ret
```
## Output  
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/29388469-7b46-4495-9040-2aeb8bc9e951)


## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h

mov al,9h;
mov bl,6h;
sub al,bl;
mov [7895h],al;

ret
```
## Output :
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/8f073c6c-3188-4eac-ac9e-9a60c978dd46)


## Multiplication alp :
```
org 100h

mov ax,0b548h;
mov bx,0a178h;
mul bx;
mov [6254h],bx;

ret
```
 ## Output  
 
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/92d94bf9-8cbf-4015-a38e-0120877b80c0)


## Division alp 
```
org 100h

mov ax,0d545h;
mov bx,0a178h;
div bx;
mov [6935h],bx;

ret
```
## Output  
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/9e2459f7-ccd5-43ac-9dda-4d714f8d78a8)

## OR Operation
```py
org 100H  
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
ret
```
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/af5ecf70-01bf-4095-9ede-3193d2a32deb)


## AND Operation
```py
org 100H  
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX; 
ret
```
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/1b1257d0-7768-430e-99ef-0857331504df)

## XOR Operation
```py
org 100H  
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H; 
XOR AX,BX;  
ret 
```
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/d5dc7a35-bf7d-4061-9cdd-d4130877fc00)


## NOT Operation
```py
org 100H  
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX; 
MOV [SI+6],AX;
ret 
```
![image](https://github.com/JivanKarthick/EXPERIMENT--01-ALP-FOR-8086/assets/121165867/3a4ee44d-6af9-43cc-bc64-866122f6cc25)







## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.




