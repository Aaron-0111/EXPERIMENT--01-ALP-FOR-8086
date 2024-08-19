# EXPERIMENT--01-ALP-FOR-8086
Name :Aaron Rajesh R
Roll no : 212223100001 
Date of experiment :19.08.2024





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
```
org 100h

MOV al,11h;
MOV bl,20h;
ADD al, bl;
MOV [6379h], al;

ret
```


## Output  
 ![Screenshot 2024-08-19 082654](https://github.com/user-attachments/assets/f5031045-c4dd-4e9a-80ff-2e3510a09758)

## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h

mov al,24h
mov bl,14h
sub al,bl
hlt

ret
```
## Output  
![Screenshot 2024-08-19 083826](https://github.com/user-attachments/assets/bfe11505-093b-4c42-95fd-3be96084c53b)

## Multiplication alp 
```
org 100h

mov al,10h
mov bl,6h
mul bl
hlt

ret
```
 ## Output  
![Screenshot 2024-08-19 083928](https://github.com/user-attachments/assets/51cdb40f-0bfd-4628-ad20-3bbc80dd925e)


## Division alp 
```
org 100h

mov al,40h
mov bl,2h
div bl
hlt

ret
```
## Output  
![Screenshot 2024-08-19 084039](https://github.com/user-attachments/assets/e013752c-7b1e-4c77-8178-0ebe46e4e4ff)

## Programs For Logical Operators

## AND
```
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX;
```
## Output
![Screenshot 2024-08-19 124946](https://github.com/user-attachments/assets/85ef2402-bd17-4890-85b7-9c137ce87419)

## OR
```
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
```
## Output
![Screenshot 2024-08-19 125813](https://github.com/user-attachments/assets/e7d37c8b-2d0f-44fb-956b-9c86223ee774)

## NOT
```
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
```
## Output
![Screenshot 2024-08-19 130038](https://github.com/user-attachments/assets/33309c7e-5972-4408-9231-6a53e3d23ed3)

## XOR
```
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H;
XOR AX,BX;
```
## Output
![Screenshot 2024-08-19 125233](https://github.com/user-attachments/assets/9845ebb0-8efb-4a33-a5ff-2cfdb3d30593)


## Result :
 
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.








