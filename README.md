# Swapping-without-3-rd-variable
Java program to Swap two variables without using third variable
import java.util.Scanner;  

public class Swap   

{  

    public static void main(String args[ ])   

    {   

        System.out.println("Enter the value of x and y");  

        Scanner input = new Scanner(System.in); 

        int x = input.nextInt();  

        int y = input.nextInt();  

        System.out.println("Before swapping numbers: "+x +" "+ y);  

        x = x + y;   

        y = x - y;   

        x = x - y;   

        System.out.println("After swapping: "+x +"  " + y);   

    }   

}  

