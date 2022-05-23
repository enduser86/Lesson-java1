# Lesson-java1
Д.З.1
package main.java;
// Задача 1
public class HomeWorkApp {
public static void main(String[] args) {
drawSquare() ;
checkSumSign() ;
printColor() ;
compareNumbers() ;
}
//Задача 2
public static void drawSquare() {
System.out.println("Orange");
System.out.println("Banana");
System.out.println("Apple");
}
//Задача 3
public static void checkSumSign() {
int a = 10;
int b = 20;
int sum = a + b;

        if (sum >= 0) {
            System.out.println("sum +");
        } else {
            System.out.println("sum -");
        }
    }
    //Задача 4
    public static void printColor() {
        int value = 150;
        if (value <= 0) {
            System.out.println("red") ;
        } else if (value > 0 & value <= 100) {
            System.out.println("yellow") ;
        } else {
            System.out.println("green") ;
        }
    }
    //Задача 5
    public static void compareNumbers() {
        int a = 30;
        int b = 40;
        if (a >= b) {
            System.out.println("a >= b");
        } else {
            System.out.println("a < b");
        }
    }
}
