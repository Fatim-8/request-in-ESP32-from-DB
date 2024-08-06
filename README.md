# request-in-ESP32-from-DB

## Introduction

ESP32 is a type of electronic circuit boards that are used for connecting to the internet and getting data. In this task, we will learn how to use ESP32 to send HTTP requests and get data from a database on the internet. This will help us expand the capabilities of the devices we use and allow us to work on more advanced Internet of Things (IoT) projects

### First, I want to show you the project page 
[project showcase](https://wokwi.com/projects/405499799569807361)

1- In this part of code, I defined each LED with its corresponding pin number:
```
#define red 34
#define purple 25
#define blue 27
#define cyan 15
#define green 4
```
2-then, Setting up LED Outputs:
```
pinMode(red, OUTPUT);
  pinMode(purple, OUTPUT);
  pinMode(blue, OUTPUT);
  pinMode(cyan, OUTPUT);
  pinMode(green, OUTPUT);
```
*here I have sets up five LED outputs on pins 34, 25, 27, 15, and 4 using the pinMode() function

3-Iterative loop to define conditions for each response:
```
 if(payload == "forward"){
        digitalWrite(red, HIGH);
      }else if(payload == "backward"){
        digitalWrite(purple, HIGH);
      }else if(payload == "stop"){
        digitalWrite(blue, HIGH);
      }else if(payload == "right"){
        digitalWrite(cyan, HIGH);
      }else if(payload == "left"){
        digitalWrite(green, HIGH);
      }
```

##### You can see:
<img width="947" alt="image" src="https://github.com/user-attachments/assets/755cd0f5-b161-4dcb-9991-3a206fc36c8a">


