# Introduction to Java

Let's go through some background on Java programming language. 

## The History and philosophy of Java

- Java was conceived by James Gosling, Patrick Naughton, Chris Warth, Ed Frank, and Mike Sheridan at Sun Microsystems, Inc. in 1991. 
- It took 18 months to develop the first working version. 
- This language was initially called 'Oak' but was renamed 'Java' in 1995.
- Based on C++ programming language.
- Platform independent.

## Object-Oriented Programming

- OOP is at the core of Java.
- The 3 OOP principles
  1. Encapsulation – the mechanism that binds together code and the data it manipulates and keeps both safe from outside interference and misuse. 
  2. Inheritance – the process by which one object acquires the properties of another object.
  3. Polymorphism – a feature that allows one interface to be used for a general class of actions.

## Java Development Kit (JDK)

The Java Development Kit is an implementation of either one of the Java Platform, Standard Edition, Java Platform, Enterprise Edition, or Java Platform, Micro Edition platforms released by Oracle Corporation in the form of a binary product aimed at Java developers on Solaris, Linux, macOS or Windows.

## Java Runtime Environment (JRE)

The Java Runtime Environment, or JRE, is a software layer that runs on top of a computer’s operating system software and provides the class libraries and other resources that a specific Java program needs to run.

## Java Virtual Machine (JVM)

A Java virtual machine (JVM) is a virtual machine that enables a computer to run Java programs as well as programs written in other languages that are also compiled to Java bytecode. The JVM is detailed by a specification that formally describes what is required in a JVM implementation.

## Your First Simple Java Program

1. Launch Eclipse.
2. Close the welcome page.
3. Create a new Java project via File > New > Java Project

![image](https://user-images.githubusercontent.com/23090837/161989239-6c1f7254-8fcd-463b-92ac-a30e75db1006.png)

4. In the New Java Project wizard, enter below details.
    - Project Name: **MyFirstJava**
    - Module: **unchecked**
    - Leave everything else to default settings and click Finish to proceed.
  
  ![image](https://user-images.githubusercontent.com/23090837/161990250-77276ea1-9ab2-4dea-994b-132ff9ec2fb7.png)

5. Next is to create a new class. Right-click project > New > Class.

![image](https://user-images.githubusercontent.com/23090837/161990976-0d1d789a-9553-464d-b676-52bec77c01f7.png)

6. In the new class wizard, enter **Hello** as the class name, then click Finish.

![image](https://user-images.githubusercontent.com/23090837/161991241-31f27095-8797-4744-b01f-713603a806e4.png)

7. Next task is to write a program to display "Hello World" message to the output console. To do that, update the class with below codes.

```java
public static void main(String[] args) {
  System.out.println("Hello World!");
}
```
Your class should now look like below.

![image](https://user-images.githubusercontent.com/23090837/161992312-3306fadc-d646-4572-9e7e-b9058d35c73e.png)

8. Now, we can run the program. To do that, go to Run > Run.

![image](https://user-images.githubusercontent.com/23090837/161992466-a7cb437c-8df2-4fd0-b812-03ccce4ff5e0.png)

9. The string “Hello World!” should be displayed in the console/output.

![image](https://user-images.githubusercontent.com/23090837/161992603-14839054-f4b2-4eb4-9163-31bbd681ba7b.png)

Congratulations! You have successfully written your first Java program!

## Java Basics

- Java programs are enclosed in a pair of curly brackets that indicates a block of codes.
- Every statement in Java must ends with a semicolon.
- Java is case-sensitive.
- Whitespace in Java program is ignored.

## Identifiers

Identifiers are used to name things, such as classes, variables, and methods.

- Must begin with a letter, underscore, or a dollar sign.
- Cannot start with a number.
- A single word.
- Case sensitive.
- Cannot use Java keywords.

## Comments

- // for single-line comments.
- /* */ for multiple-lines comments.
- /** */ for Javadoc comments.

## The Java Keywords

|    |   |   |  |   |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| abstract  | continue  | for  | new  | switch  |
| assert  | default | goto  | package  | synchronized  |
| boolean  | do  | if  | private  | this  |
| break  | double  | implements  | protected  | throw  |
| byte  | else  | import  | public  | throws  |
| case  | enum  | instanceof  | return  | transient  |
| catch  | extends  | int  | short  | try  |
| char  | final  | interface  | static  | void  |
| class  | finally  | long  | strictfp  | volatile  |
| const  | float  | native  | super  | while  |

## The Java Class Libraries

Full list of Java class libraries can be found at the official page  https://docs.oracle.com/en/java/javase/11/docs/api/

![image](https://user-images.githubusercontent.com/23090837/161996002-d2716860-5089-4064-9b4d-88d1867ae952.png)
