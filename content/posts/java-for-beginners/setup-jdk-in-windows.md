+++
draft = false
author = "Raj Poudyal"
title = "Setup JDK in Windows"
date = "2022-05-26"
description = "A detailed blog post that shows how to set up JDK in Windows."
featured = false
comment = true
toc = true
categories = [
"Java"
]
tags = [
"JDK",
"Windows",
]
images = [
]
+++

This article explains method of installing of JDK in Windows. Also to verify JDK after instillation. 

<!--more-->

## Background

> The Java Development Kit (JDK) is a distribution of Java Technology by Oracle Corporation. It implements the Java Language Specification (JLS) and the Java Virtual Machine Specification (JVMS) and provides the Standard Edition (SE) of the Java Application Programming Interface (API). It provides software for working with Java applications. Examples of included software are the virtual machine, a compiler, performance monitoring tools, a debugger, and other utilities that Oracle considers useful for a Java programmer. - [wikipedia.org](https://en.wikipedia.org/wiki/Java_Development_Kit)

## Download JDK 

1. Search JDK download at search engine,

2. Open Java download of oracle website,
![](/images/setup-jdk-in-windows/1.jpg)

3. Choose the correct OS according for specific JDK (Windows,Mac,Linux),
![](/images/setup-jdk-in-windows/2.jpg)

4. Scrool or search for compactiable installer for your platform,
![](/images/setup-jdk-in-windows/3.jpg)

5. Click on related installer and accept terms and condition then click on download,
![](/images/setup-jdk-in-windows/4.jpg)

6. After some time download will be completed.
  
## Install JDK
  1. Once the download is complete go to downloads at My PC where you find the JDK application,

  ![](5.jpg)
  2. Then, execute(open) the file to begin the installation of JDK,

  3. After you double click the JDK file, a pop up asking you where your source java file will be (You can choose to change but better to stick with original location). Click next to all criteria,
  4. Then, after some time JDK will be install in your device, 



## Set environment variable
1. Go to search menu and search advanced system settings, 

![](8.jpg)

2. Select Advanced System Setting.
Click on Environment Variables (at the bottom right corner),

![](9.jpg)

3. There will be two environment variables, one is the User variable and another is a System variable.


4. If path and classpath variables are already present in System Variable, click on it to edit. Otherwise, set a new variable.
5. Set the path variable by adding the following directory path.
  _______________________
set path environment variable
6. Set the classpath variable by adding the following classpath directory path.
  _______________________-_
set classpath environment variable.


Click on OK.


Now you have done with Java JDK setup. 



## Verify Installiation
We can use javac -version to find out the version of the installed JDK. 
1. We have to open command prompt,
2. Then, type javac -version and hit enter,
3. JDK version will be displayed.

![](6.jpg)
 In the below example, the JDK version is 18.0.1



