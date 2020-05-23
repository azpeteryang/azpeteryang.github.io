---
title: "Java Teaching"
collection: teaching
type: "Graduate course"
venue: 
date: 
location: "Atlanta, GA"
---
# Simple Introduction to Java

JRE includes {JVM + Runtime Library}  
JDK includes JRE + {Compiler,debugger,etc.}  
# Variable
short: 2 bytes;  
int: 4 bytes;  
long: 8 bytes;  
float: 4 bytes;  
double: 8 bytes;  
char: 2 bytes  
There are two types of java variables: basic type and reference type  
int  
float, double  
boolean  
char  
String a = "hello"; (reference type)
# Calculation
There might be some errors when calculating two float numbers:
```java
public class Main{
    public static void main(String[] args){
        double x = 1.0/10;
        double y = 1-9.0/10;
        double r = Math.abs(x-y);
        if(r<0.00001){
            System.out.println("x=y");
        }
        else{
            System.out.println("x!=y");
        }
    }
}

```

HW1: The way to calculate a Quadratic Equation of One Variable:
```java
public class Main {
    public static void main(String[] args) {
        double a = 1.0;
        double b = 3.0;
        double c = -4.0;
        double r1 = 0;
        double r2 = 0;
        
        r1 = (-b + Math.sqrt(b*b-4*a*c))/(2*a);
        r2 = (-b - Math.sqrt(b*b-4*a*c))/(2*a);
        
        System.out.println(r1);
        System.out.println(r2);
        System.out.println(r1 == 1 && r2 == -4 ? "right" : "wrong");
    }
}

```

The new way to represent a char:
```java
char a = '\u3e3d'        // Use Hex to represent
```
