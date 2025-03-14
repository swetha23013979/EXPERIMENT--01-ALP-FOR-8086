# EXPERIMENT--01-ALP-FOR-8086
Name : Swetha D

Roll no : 212223040222


Date of experiment : 13/3/25





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
Mov AL,74H
Mov BL,69H
ADD AL,BL 
HLT
```


## Output  
 ![420830109-43e3daaa-ccc9-4cae-94e3-d24347c7db72](https://github.com/user-attachments/assets/cbe6a383-7ded-41d6-8473-b4ab85ed15be)

## Subtraction   of 8 bit numbers  ALP 
```
Mov AL,74H
Mov BL,69H
SUB AL,BL 
HLT
```
 
## Output 
![420830475-7ef5307b-f4f1-49e6-833e-5f2f11704d30](https://github.com/user-attachments/assets/df5a3226-070d-4e3e-bbf3-207fefa9267f)


## Multiplication alp 
```
org 100h
Mov AL,74H
Mov BL,69H
MUL BL 
HLT 
RET
```
 ## Output  
![420830711-14342ece-6df1-43b8-b597-78ec95c88e3d](https://github.com/user-attachments/assets/0642b0ec-7bbf-4aaa-8a57-c6ad4256fb3f)


## Division alp 
```
org 100h
Mov AL,74H
Mov BL,69H
DIV BL 
HLT 
RET
```

## Output  
![420831148-ab6b917e-76cf-48ae-a87d-efec83491cda](https://github.com/user-attachments/assets/93c89023-c094-4984-852f-4dd8666206f9)
## AND ALP
```
Mov AL,33H
Mov BL,44H
AND AL,BL
HLT 
````
## Output
![420831473-928fe527-1941-44c6-9234-2aad303f9a29](https://github.com/user-attachments/assets/f045c2a1-0bfa-4571-8560-3305332bbd6a)

## OR ALP
```
Mov AL,33H
Mov BL,44H
OR AL,BL
HLT
```
## Output
![420831602-029e8d02-b386-4afb-a307-bf43e5d91a0a](https://github.com/user-attachments/assets/7d83ff30-ae9f-4a70-9d5c-bfcb68ce8f19)

## NOT ALP
```
Mov AL,33H
NOT AL,BL
HLT
```

## Output
![420831826-00b19706-1527-4289-ba14-a331c0ed0b83](https://github.com/user-attachments/assets/504353fb-5316-484c-929a-f70444dc149c)

## XOR ALP
```
org 100h
Mov AL,66H
MOV BL,77h
XOR AL,BL
HLT     
ret
```
## Output

![420831982-d5efd4c3-a2b5-4caa-91ee-ab1dc3782ea5](https://github.com/user-attachments/assets/b5cd50cd-20c0-4013-9831-d2c9f22d2e7f)


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








