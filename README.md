# JAVA-scenario-Question-calculator
I have done a *JAVA scenario Question calculator 
Program:



import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int a=sc.nextInt();
	    int b=sc.nextInt();
	    System.out.println("Addition");
	    System.out.println("Subraction");
	    System.out.println("Multiplication");
	    System.out.println("Division");
	    int c=sc.nextInt();
	    switch(c){
	        case 1:
	            System.out.println("1.Addition of"+(a+b));
	            break;
	        case 2:
	            System.out.println("2.Subraction of"+(a-b));
	            break;
	        case 3:
	            System.out.println("3.Multiplication of"+(a*b));
	            break;
	        case 4:
	            System.out.println("4.Division of"+(a/b));
	            break;
	            default :
	            System.out.print("error");
	    }}}
