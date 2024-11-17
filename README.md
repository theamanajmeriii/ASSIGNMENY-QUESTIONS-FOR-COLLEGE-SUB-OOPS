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

import java.util.Scanner; 
public class p6 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the year:"); 
        int year= sc.nextInt(); 
        if(year%4==0||year%400==0){ 
            System.out.println("it is a leap year"); 
        } 
        else if(year%100==0){ 
            System.out.println("it is not a leap year"); 
        } 
        else { 
            System.out.println("it is not a leap year"); 
        } 
    } 
} 


output: 
enter the year: 
1342 
it is not a leap year

7. WRITE A JAVA PROGRAM FOR FOLLOWING GRADING SYSTEM. NOTE:
Percentage>=90%  : Grade A   
Percentage>=80% : Grade B  
Percentage>=70% : Grade C   
Percentage>=60% : Grade D   
Percentage>=40% : Grade E  
Percentage<40% : Grade F

import java.util.Scanner; 
public class p7 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the percentage"); 
        int percent=sc.nextInt(); 
        if(percent>=90) 
            System.out.println("Grade A"); 
        else if(percent>=80) 
            System.out.println("Grade B"); 
        else if(percent>=70) 
            System.out.println("Grade C"); 
        else if(percent>=60) 
            System.out.println("Grade D"); 
        else if(percent>=40)  
                            System.out.println("Grade E"); 
        else 
            System.out.println("Grade F"); 
    } 
} 


output: 
enter the percentage 
45 
Grade E


8. Write a Java program to check whether a number is divisible by a 
number given by user.

import javax.swing.*; 
import java.util.Scanner; 
 
public class p8 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number"); 
        int a=sc.nextInt(); 
        //to check  whether a given number is divisble by given number or not 
        if(a%a==0){ 
            System.out.println("the nmumber is divisible"); 
        } 
        else if(a%a!=0){ 
            System.out.println("the number is not divisible "); 
        } 
        else { 
            System.out.println("the number is not divisible"); 
        } 
    } 
} 


output: 
enter a number 
34 
the nmumber is divisible by34

9. Write a Java program to calculate factorial of 12.  
//create a factorial 12 
public class p9 { 
    public static void main(String[] args) { 
        int i, fact=1; 
        int number=12; 
        for(i=1;i<=number;i++){ 
            fact=fact*i; 
        } 
        System.out.println("factorial of"+number+ "is"  +fact); 
    } 


output: 
factorial of12is479001600 
 
10. Write a Java program for Fibonacci series.

ublic class p11 { 
    public static void main(String[] args) { 
        int n1=0,n2=1,n3,i,count=10; 
        System.out.print(n1+" "+n2);//printing 0 and 1 
 
        for(i=2;i<count;++i)//loop starts from 2 because 0 and 1 are already printed 
        { 
            n3=n1+n2; 
            System.out.print(" "+n3); 
            n1=n2; 
            n2=n3; 
        } 
 
    } 
}


output: 
0 1 1 2 3 5 8 13 21 34

    
 
 
11. Write a Java program to reverse a number.

    
public class p19 { 
    public static void main(String[] args) { 
        int num = 1234567, reversed = 0; 
        for(;num != 0; num /= 10) { 
            int digit = num % 10; 
            reversed = reversed * 10 + digit; 
        } 
        System.out.println("Reversed Number: " + reversed); 
    } 
} 


output: 
Reversed Number: 7654321 
 
12. Admission to a professional course is subject to the following 
conditions:  
(a) marks in Mathematics >= 60  
(b) marks in Physics >=50  
(c) marks in Chemistry >=40  
(d) Total in all 3 subjects >=200  
(Or) Total in Maths & Physics>=150 Given the marks in the 3 subjects of 
n (user input)  
students, write a program to process the applications to list the eligible 
candidates.


import javax.swing.*; 
import java.util.Scanner; 
public class p12 { 
    public static void main(String[] args) { 
        Scanner sc = new Scanner(System.in); 
        System.out.println("enter the marks oof three subjects:"); 
        int phy = sc.nextInt(); 
        int mat = sc.nextInt(); 
        int chem = sc.nextInt(); 
        int t = phy + mat + chem; 
        int pm = phy + mat; 
        if (phy >= 70 && chem >= 60 && mat >= 70 
                && (t >= 225 || pm >= 150)) ; 
        System.out.println("eligible"); 
        else{ 
            System.out.println("not eligible"); 
 
        } 
    } 
} 
output:

13. Write a Java program to calculate the sum of natural numbers up to 
a certain range.  
public class p13 { 
    public static void main(String[] args) { 
        int n = 100; 
        int sum=0; 
        for(int i=0;i<n;i++) { 
            sum += i; 
        } 
            System.out.println("sum is "+sum); 
        } 
} 
output: 
sum is 4950

14. Write a Java program to print all multiple of 10 between a given 
interval.  
public class p14 { 
    public static void main(String[] args) { 
        int n=10; 
        for(int i=1;i<11;i++){ 
            System.out.println(10*i); 
        } 
    } 
} 
output: 
10 
20 
30 
40 
50 
60 
70 
80 
90
100


15. Write a Java program to generate multiplication table. 
import java.util.Scanner; 
public class p15 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number"); 
        int n= sc.nextInt(); 
        for (int i=0;i<11;i++){ 
            System.out.println(i*n); 
        } 
    } 
} 
output: 
enter a number 4 
0 4 
8 
12  16  20  24  28  32  36  40

16. Write a Java program to find HCF of two Numbers.  
 
public class p16 { 
    public static void main(String[] args) { 
        int num1 = 24, num2 = 36, hcf=0; 
        for (int i = 1; i <= num1 || i <= num2; i++) 
        { 
            if (num1 % i == 0 && num2 % i == 0) 
                hcf = i; 
        } 
        System.out.println("The HCF: "+ hcf); 
    } 
} 
output: 
The HCF: 12 

public class p17 { 
    public static void main(String[] args) { 
        // Numbers 
        int a = 15, b = 25; 
 
        // Checking for the largest 
        // Number between them 
        int ans = (a > b) ? a : b; 
 
        // Checking for a smallest number that 
        // can de divided by both numbers 
        while (true) { 
            if (ans % a == 0 && ans % b == 0) 
                break; 
            ans++; 
        } 
 
        // Printing the Result 
        System.out.println("LCM of " + a + " and " + b 
                + " : " + ans); 
    } 
} 
output: 
LCM of 15 and 25 : 75

17. Write a Java program to find LCM of two Numbers.  
public class p17 { 
    public static void main(String[] args) { 
        // Numbers 
        int a = 15, b = 25; 
 
        // Checking for the largest 
        // Number between them 
        int ans = (a > b) ? a : b; 
 
        // Checking for a smallest number that 
        // can de divided by both numbers 
        while (true) { 
            if (ans % a == 0 && ans % b == 0) 
                break; 
            ans++; 
        } 
 
        // Printing the Result 
        System.out.println("LCM of " + a + " and " + b 
                + " : " + ans); 
    } 
} 
output: 
LCM of 15 and 25 : 75

18. Write a Java program to count the number of digits of an integer 
public class p18 { 
    public static void main(String[] args) { 
        int count = 0, num = 20000; 
        while (num != 0) { 
            // num = num/10 
            num /= 10; 
            ++count; 
        } 
        System.out.println("Number of digits: " + count); 
    } 
} 
output: 
Number of digits: 5 

19. Write a Java program to check whether a number is palindrome or 
not.  
import java.util.Scanner; 
public class p19 { 
    public static void main(String args[]){ 
        Scanner sc=new Scanner(System.in); 
        System.out.print("Input a number: "); 
        int n = sc.nextInt(); 
        int sum = 0, r; 
        int temp = n; 
        while(n>0) 
        { 
            r = n % 10; 
            sum = (sum*10)+r; 
            n = n/10; 
        } 
        if(temp==sum) 
            System.out.println("It is a Palindrome number."); 
        else 
            System.out.println("Not a palindrome"); 
    } 
} 
output: 
Input a number: 12321 
It is a Palindrome number.

20. Write a Java program to check whether a number is prime or not.  
import java.util.Scanner; 
public class p20 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number:"); 
        int a=sc.nextInt(); 
        if (a==0||a==1){ 
            return; 
        } 
        for (int i=2;i<a/2;++i){ 
            if(a%i==0){ 
                System.out.println("not a prime number"); 
            } 
            else{ 
                System.out.println("prime number"); 
            } 
        } 
    } 
} 
output: 
enter a number: 
7 
prime number

21. Write a Java program to convert a Binary Number to Decimal and 
Decimal to Binary.  
public class p21 { 
    public static void main(String[] args) { 
        //declare variable to store decimal number,quotient and array 
        int quot,i=1,j; 
        int [] arr=new int[100]; 
        //create a scanner input class 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a decimal number:"); 
        int dec_num= sc.nextInt(); 
        //initialize the quotient , 
        quot=dec_num; 
        // Convert the decimal number to binary and store binary digits 
        while (quot != 0) { 
            arr[i++] = quot % 2; 
            quot = quot / 2; 
        } 
 
        // Display the binary representation of the decimal number 
        System.out.print("Binary number is: "); 
        for (j = i - 1; j > 0; j--) { 
            System.out.print(arr[j]); 
        } 
        System.out.print("\n"); 
    } 
} 
output: 
enter a decimal number: 
23 
Binary number is: 10111

22. Write a Java program to find median of a set of numbers.  
mport java.util.Arrays; 
public class p22 { 
    public static void main(String[] args) { 
        // Define and initialize an array of integers 
        int[] nums = {10, 2, 38, 22, 38, 23}; 
        // Display the original array 
        System.out.println("Original array: " + Arrays.toString(nums)); 
        // Calculate and display the median of the array 
        System.out.println("Median of the said array of integers: " + getMedian(nums)); 
        // Define and initialize another array of integers 
        int[] nums1 = {10, 2, 38, 23, 38, 23, 21}; 
        // Display the original array 
        System.out.println("\nOriginal array: " + Arrays.toString(nums1)); 
        // Calculate and display the median of the second array 
        System.out.println("Median of the said array of integers: " + getMedian(nums1)); 
    } 
    public static int getMedian(int[] array) { 
        // Check if the length of the array is even 
        if (array.length % 2 == 0) { 
            // Calculate the median for even-sized arrays 
            int mid = array.length / 2; 
            return (array[mid] + array[mid - 1]) / 2; 
        } 
        // Calculate the median for odd-sized arrays 
        return array[array.length / 2]; 
    } 
} 
output: 
Original array: [10, 2, 38, 22, 38, 23] 
Median of the said array of integers: 30 
Original array: [10, 2, 38, 23, 38, 23, 21] 
Median of the said array of integers: 23

23. Write Java programs for the patterns given bellow:  
(a) 1      
      2 3 4  
      5 6 7 8 9  
(b)      1  
         2 1 2  
      3 2 1 2 3  
   4 3 2 1 2 3 4 
public class p23 { 
    public static void main(String[] args) { 
        int a = 1; 
        for (int i = 1; i <= 4; i++) { 
            for (int j = 1; j <= i; j++) { 
                System.out.print(a++ + "\t"); 
            } 
            System.out.println(); 
        } 
    } 
} 
output: 
1 
2     3    4 
5     6     7     8     9

24. Write a Java program to calculate Sum & Average of an integer 
array.

package com.company; 
//import util.java.s 
import java.util.Scanner; 
public class p24 { 
    public static void main(String[] args) { 
        int n, sum = 0; 
        float average; 
        Scanner sc = new Scanner(System.in); 
        System.out.print("Enter no. of elements you want in array:"); 
        n = sc.nextInt(); 
        int a[] = new int[n]; 
        System.out.println("Enter all the elements:"); 
        for(int i = 0; i < n ; i++) 
        { 
            a[i] = sc.nextInt(); 
            sum = sum + a[i]; 
        } 
        System.out.println("Sum:"+sum); 
        average = (float)sum / n; 
        System.out.println("Average:"+average); 
    } 
} 

output: 
Enter no. of elements you want in array:5 
Enter all the elements: 
23 12 56 45 33 
Sum:169 
Average:33.8


25. Write a Java program to implement stack using array.
    
 public class p25 {private int maxSize; 
    private Object[] stackArray; 
    private int top; 
 
    public p25(int size) { 
        maxSize = size; 
        stackArray = new Object[maxSize]; 
        top = -1; 
    } 
 
    public void push(Object value) { 
        if (isFull()) { 
            System.out.println("Stack is full. Cannot push element."); 
            return; 
        } 
        top++; 
        stackArray[top] = value; 
    } 
 
    public Object pop() { 
        if (isEmpty()) { 
            System.out.println("Stack is empty. Cannot pop element."); 
            return -1; 
        } 
        int oldTop = top; 
        top--; 
        stackArray[oldTop] = null; 
        return stackArray[oldTop]; 
    } 
 
    public Object peek() { 
        if (isEmpty()) { 
            System.out.println("Stack is empty. Cannot peek element."); 
            return -1; 
        } 
        return stackArray[top]; 
    } 
 
    public boolean isEmpty() { 
        return (top == -1); 
    } 
 
    public boolean isFull() { 
        return (top == maxSize - 1); 
    } 
 
    @Override 
    public String toString() { 
        return "Stack: " + Arrays.toString(stackArray); 
    } 
} 

26. Write a Java program to implement Queue using array.

class Queue {
    private int[] arr; // Array to store the elements
    private int front; // Front of the queue
    private int rear;  // Rear of the queue
    private int capacity; // Maximum capacity of the queue
    private int size;  // Current size of the queue

    // Constructor to initialize the queue
    public Queue(int capacity) {
        this.capacity = capacity;
        arr = new int[capacity];
        front = 0;
        rear = -1;
        size = 0;
    }

    // Method to add an element to the queue
    public void enqueue(int element) {
        if (isFull()) {
            System.out.println("Queue is full. Cannot enqueue " + element);
            return;
        }
        rear = (rear + 1) % capacity; // Wrap around if rear exceeds capacity
        arr[rear] = element;
        size++;
        System.out.println("Enqueued: " + element);
    }

    // Method to remove an element from the queue
    public int dequeue() {
        if (isEmpty()) {
            System.out.println("Queue is empty. Cannot dequeue.");
            return -1; // Return a sentinel value for an empty queue
        }
        int element = arr[front];
        front = (front + 1) % capacity; // Wrap around if front exceeds capacity
        size--;
        System.out.println("Dequeued: " + element);
        return element;
    }

    // Method to check if the queue is empty
    public boolean isEmpty() {
        return size == 0;
    }

    // Method to check if the queue is full
    public boolean isFull() {
        return size == capacity;
    }

    // Method to display the queue
    public void display() {
        if (isEmpty()) {
            System.out.println("Queue is empty.");
            return;
        }
        System.out.print("Queue: ");
        for (int i = 0; i < size; i++) {
            System.out.print(arr[(front + i) % capacity] + " ");
        }
        System.out.println();
    }

    // Main method to test the Queue implementation
    public static void main(String[] args) {
        Queue queue = new Queue(5); // Create a queue with capacity 5

        queue.enqueue(10);
        queue.enqueue(20);
        queue.enqueue(30);
        queue.enqueue(40);
        queue.enqueue(50);

        queue.display();

        queue.dequeue();
        queue.dequeue();

        queue.display();

        queue.enqueue(60);
        queue.enqueue(70);

        queue.display();
    }
}

output:
Enqueued: 10
Enqueued: 20
Enqueued: 30
Enqueued: 40
Enqueued: 50
Queue: 10 20 30 40 50
Dequeued: 10
Dequeued: 20
Queue: 30 40 50
Enqueued: 60
Enqueued: 70
Queue: 30 40 50 60 70


27. Write a Java program to enter n elements in an array and find 
smallest number among them.  
public class p27 { 
    public static void main(String[] args) 
    { 
        // Either we can initialize array elements or can 
        // get input from user. Always it is best to get 
        // input from user and form the array 
        int[] initializedArray 
                = new int[] { 25, 110, 74, 75, 5 }; 
        System.out.println("Given array "); 
        for (int i = 0; i < initializedArray.length; i++) { 
            System.out.println(initializedArray[i]); 
        } 
        // Initialize minValue with first element of array. 
        int minValue = initializedArray[0]; 
        // Loop through the array 
        for (int i = 0; i < initializedArray.length; i++) { 
            // Compare elements of array with minValue and 
            // if condition true, make minValue to that 
            // element 
            if (initializedArray[i] < minValue) 
                minValue = initializedArray[i]; 
        } 
        System.out.println("Smallest element present in given array: " + minValue); 
    } 
} 


output: 
Given array  
25   110  74  75  5 
Smallest element present in given array: 5

28. Write Java program to find the sum of all odd numbers in a array.   
import java.util.Scanner; 
public class p28 { 
    static Scanner sc=new Scanner(System.in); 
    public static void main(String[] args){ 
        int Size, i, OddSum = 0; 
        sc = new Scanner(System.in); 
        System.out.print(" Please Enter Number of elements in an array : "); 
        Size = sc.nextInt(); 
        int [] a = new int[Size]; 
        System.out.print(" Please Enter " + Size + " elements of an Array  : "); 
        for (i = 0; i < Size; i++) 
        { 
            a[i] = sc.nextInt(); 
        } 
        for(i = 0; i < Size; i++) 
        { 
            if(a[i] % 2 != 0) 
            { 
                OddSum = OddSum + a[i]; 
            } 
        } 
        System.out.println("\n The Sum of Odd Numbers in this Array = " + OddSum); 
    } 
} 


output: 
Please Enter Number of elements in an array : 5 
 Please Enter 5 elements of an Array  : 12 34 23 67 45 
The Sum of Odd Numbers in this Array = 135

29. Write a Java program to find duplicate elements in a 1D array and 
find their frequency of occurrence.  
mport java.util.Arrays; 
public class p29 { 
    //main method 
    public static void main(String[] args) { 
        //Declare and initialize the array elements 
        int[] array = { 2, 3, 5, 4, 3, 1, 3, 2, 1, }; 
        //sorting an array 
        Arrays.sort(array); 
        //declaring the variables 
        int i,j,frequency; 
        System.out.println("These elements are repeated along with its frequency-"); 
        //loop for logic implementation 
        for(i=0; i<array.length; i++){ 
            frequency = 1; 
            for(j=i+1; j<array.length; j++){ 
                if(array[j] == array[i]){ 
                    frequency++; 
                } else { 
                    break; 
                } 
            } 
            i=j-1; 
            if(frequency > 1){ 
 
                //printing the output 
                System.out.println(array[i] + " --> " + frequency); 
            } 
        } 
    } 
 
}


output: 
These elements are repeated along with its frequency- 
1 --> 2 
2 --> 2 
3 --> 3

30. Write a Java program to print every alternate number of a given 
array  
public class p30 { 
    public static void main( String args[] ) { 
        //initialize array 
        int[] arr = {11, 12, 13, 14, 15}; 
        //array length 
        int n = arr.length; 
        // loop through the array and increment by 2 
        for(int i=0; i<n; i = i+2){ 
            //print element 
            System.out.println(arr[i]); 
        } 
    } 
} 


output: 
11 
13 
15 

31. Write a Java program to show 0-arguments constructor.  
public class p31 { 
    int i; 
    // constructor with no parameter 
    private p31() { 
        i = 5; 
        System.out.println("Constructor is called"); 
    } 
    public static void main(String[] args) { 
        // calling the constructor without any parameter 
        p31 obj = new p31(); 
        System.out.println("Value of i: " + obj.i); 
    } 
} 


output: 
Constructor is called 
Value of i: 5

32. Write a Java program to show parameterized constructor.  
import java.util.Scanner; 
public class p32{ 
    public static class Edureka{ 
        String studentName; 
        int studentAge; 
        //constructor 
        Edureka(String name, int age){ 
            studentName = name; 
            studentAge = age; 
        } 
        void display(){ 
            System.out.println(studentName+ " "+studentAge); 
        } 
        public static void main(String args[]) 
        { 
            Edureka myObj = new Edureka("Manan" , 19); 
            myObj.display(); 
        } 
    } 
 
} 


output: 
Manan 19

33. Write a class, Commission, which has an instance variable, sales; an 
appropriate constructor; and a method, commission() that returns the 
commission.Now write a demo class to test the Commission class by 
reading a sale from the user, using it to create a Commission object 
after validating that the value is not negative. Finally, call the 
commission() method to get and print the commission. If the sales are 
negative, your demo should print the message “Invalid Input”.  
mport java.util.Scanner; 
 
public class p29{ 
        public static class Commission 
        { 
            String name; 
            int emp_no; 
            int sal; 
            double comm; 
            void input() { 
                Scanner sc=new Scanner(System.in); 
                System.out.print("Enter employee name: "); 
                name = sc.nextLine(); 
                System.out.print("Enter employee number: "); 
                emp_no = sc.nextInt(); 
                System.out.print("Enter monthly sales value: "); 
                sal = sc.nextInt(); 
            } 
            void compute() { 
                if (sal <= 50000) { 
                    comm = 5.0 / 100.0 * sal; 
                } 
                else if (sal <= 80000) { 
                    comm = 8.0 / 100.0 * sal; 
                } 
                else if (sal <= 100000) { 
                    comm = 10.0 / 100.0 * sal; 
                } 
                else if(sal<0){ 
                    System.out.println("invalid output"); 
                } 
                else { 
                    comm = 12.0 / 100.0 * sal; 
                } 
            } 
            void display() { 
                System.out.println("Employee name: " + name); 
                System.out.println("Employee Number: " + emp_no); 
                System.out.println("Monthly Sales: " + sal); 
                System.out.println("Commission: " + comm); 
            } 
            public void main(String args[]) { 
                com.company.p33.Commission obj = new com.company.p33.Commission(); 
                obj.input(); 
                obj.compute(); 
                obj.display(); 
            } 
        } 
} 
output:
