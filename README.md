# Recursion-factorial-

Factorial of a number

import java.util.*;


class Recursion{
     static int Factnum(int n){

        if(n==1 || n==0){
            return 1;
        }
        return n*Factnum(n-1);
    }

    public static void main(String... str) {
        System.out.println("Enter the value of n : ");
        Scanner sc = new Scanner(System.in);
        int n=sc.nextInt();
        System.out.println("The factorial is : "+ Factnum(n));


    }
}






/*
Enter the value of n : 
5
The factorial is : 120
 */
