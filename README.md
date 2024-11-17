# ASSIGNMENY-QUESTIONS-FOR-COLLEGE-SUB-OOPS
JAVA ASSIGNMENT 

1. WRITE A JAVA PROGRAM TO CHANGE TEMPERATURE FROM CELCIUS TO FAHRENHEIT AND VICE VERSA.

import java.util.Scanner; 
public class p1 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the value in celcius:"); 
        int celcius= sc.nextInt(); 
        int farenhite=((9*celcius)/5)+32; 
        System.out.println("the value in farenhite is:"+farenhite); 
    } 
} 


output: 
enter the value in celcius: 
30 
the value in farenhite is:86 

2. WRITE A JAVA PROGRAM TO CHCEK IF A NUMBER IS POSITIVE OR NEGATIVE.
   
package com.company; 
import java.util.Scanner; 
public class p2 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number"); 
        int a= sc.nextInt(); 
        if(a>=0){ 
            System.out.println("the number is positive "); 
        } 
        else { 
            System.out.println("the number is negative"); 
        } 
    } 
} 


output 
enter a number 
45
the number is positive  
enter a number -45 
the number is negative 

3. WRITE A JAVA PROGRAM TO FIND MAXIMUM OF THREE NUMBERS.


import java.util.Scanner; 
public class p3 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter three number:"); 
        int a= sc.nextInt(); 
        int b= sc.nextInt(); 
        int c= sc.nextInt(); 
        if(a>b&&a>c){ 
            System.out.println("a is greater"); 
        } 
        else if(b>a&&b>c){ 
            System.out.println("b is greater"); 
        } 
        else{ 
            System.out.println("c is greater"); 
        } 
    } 
} 


output 
enter three number: 
4 5 2 
b is greater

4. WRTE A PROGRAM TO SWAP TWO NUMBERS.

import java.util.Scanner; 
public class p4 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        int num1= sc.nextInt(); 
        int num2= sc.nextInt(); 
        swap(num1,num2); 
    } 
    private static boolean swap(int num1, int num2) { 
        int temp =num1; 
        num1=num2; 
        num2=temp; 
        System.out.println(swap(4,5)); 
        return false; 
    } 
}

output
Enter the first number: 4
Enter the second number: 5
After swapping: 
First number: 5
Second number: 4

5. WRITE A JAVA PROGRAM TO CONVET MILES TO KILOMETRES.
import java.util.Scanner; 
public class p5 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the value of km"); 
        int km= sc.nextInt(); 
        double miles=0.612*km; 
        System.out.println("the value in miles is:"); 
        System.out.println(miles); 
    } 


output
enter the value of km 
3 
the value in miles is: 
1.8359999999999999

6. WRITE A JAVA PROGRAM TO CHCEK WHETHER A YEAR IS LEAP YEAR OR NOT.
