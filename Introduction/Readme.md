# JAVA Introduction

Java is a high-level, object-oriented programming language developed by Sun Microsystems in 1995.

It is mostly used for building **applications**:

- Web applications  
- Android apps 
-  Enterprise systems

Java is guaranteed to be “Write Once, Run Anywhere”

### Java is:   
- Object-oriented
- Platform independent
- Simple & secure
- Architecture neutral
- Portable
- Robust
- Interpreted
- High performance
- Dynamic
```java
Hello World Program in Java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```
### Explanation:

*public class HelloWorld* → Defines the class named HelloWorld

*public static void main(String[] args)* → Entry point of every Java program

- JVM looks for main() to start execution

*System.out.println()* → Prints message to console



### Features of Java

- Object-Oriented Programming (OOP)
- Platform Independence
- Robust & Secure
- Multithreading & Concurrency
- Rich API & Standard Libraries
- Frameworks for Enterprise & Web Development
- Open Source Libraries
- Maintainability & Scalability

### How Java Works?

Java is compiled into bytecode, then interpreted into machine code.

**Flow:**   
*Source Code → Compiled → Bytecode → Interpreted → Machine Code*

### JDK (Java Development Kit)

Collection of tools for developing and running Java programs

### JRE (Java Runtime Environment)

Helps execute Java programs

#### Naming Conventions in Java
1. **<u>Classes</u>**

Use nouns  
First letter capital (PascalCase)

**Example**: MyClass, Nitin, SchoolName

2. **<u>Functions & Variables</u>**

Use lowerCamelCase

**Example**: userName, totalAmount, myName

### JVM (Java Virtual Machine)

Core component of **JRE**.  
Runs Java programs on any platform  
Acts as interpreter between Java bytecode & hardware  
Enables *“Write Once, Run Anywhere”*

#### JVM Process:

Loads bytecode  
    ⬇  
Verifies it   
    ⬇    
Links it   
    ⬇    
Executes it   

**Execution Methods:**

- Interpreter
- JIT (Just-In-Time) Compiler


#### Architecture of JVM
**Memory Areas:**   
Method Area  
Heap   
Stack   
PC Register   
Native Method Stack    

**Class Loader Subsystem Types:**  
Bootstrap Class Loader   
Extension Class Loader   
System/Application Class Loader  

**Linking Steps:**   
Verification  
Preparation  
Resolution

**Initialization:**   
Assigns values to static variables   
Executes static blocks   
Execution Engine  
Interpreter  
JIT Compiler  
Garbage Collector   

**JNI (Java Native Interface)**  
Interface to interact with native libraries (C, C++)

### Java Runtime Environment (JRE)

**Includes:**  
JVM  
Library set  
Required to run Java programs

**Handles:**    
Class loading  
Memory checking   
Accessing system resources  

### Working of JRE

Class Loader

Bytecode Verifier

Interpreter

### Java Development Kit (JDK)

Complete development kit
+
Includes:  
Compiler  
Debugger  
Tools

**Editions:**  
Java SE (Standard Edition)   
Java EE (Enterprise Edition)   
Java ME (Micro Edition) 

#### Contents of JDK

JRE
+
Java interpreter
+
Java compiler (javac)
+
Jar archiver
+
Other essential tools

## C vs C++ vs Java

Comparison: C vs C++ vs Java   

|Feature	       |     C	   |      C++     |	Java                 |
|------------------|-----------|--------------|----------------------|
|Type	           | Structured|	OOP       |	OOP                  |
|Compilation	   | Compiled  |Compiled      |	Compiled &Interpreted|
|Level	           | Middle    |	High      |	High                 |
|Platform	       | Dependent |	Dependent |	Independent          |
|OOP	           |    No	   |Yes	          | Yes                  |  
|Robust	           |    No	   |Yes	          | Yes                  |
|Exception Handling|	No	   |Yes	          | Yes                  |
|Threading	       |    No	   |Yes	          | Yes                  |

