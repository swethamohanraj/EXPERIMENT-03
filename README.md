# EXPERIMENT-03 JAVA PROGRAM TO FIND NUMBER OF DAYS IN A MONTH
## AIM:
To find number of days in a month using java programming language.

## PROCEDURE:
1.Import required packages.

2.Declare main method with the signature "public static void main(String[] args)".

3.Get the month input from user.

4.Use switch method to find the number of days for the given month input.

5.Display the output.

## PROGRAM:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.println("Enter the month number: ");
        int month=input.nextInt();
        switch(month)
        {
            case 1:
                System.out.println("31 days");
                break;
            case 2:
                System.out.println("28 days");
                break;
            case 3:
                System.out.println("31 days");
                break;
            case 4:
                System.out.println("30 days");
                break;
            case 5:
                System.out.println("31 days");
                break;
            case 6:
                System.out.println("30 days");
                break;
            case 7:
                System.out.println("31 days");
                break;
            case 8:
                System.out.println("31 days");
                break;
            case 9:
                System.out.println("30 days");
                break;
            case 10:
                System.out.println("31 days");
                break;
            case 11:
                System.out.println("30 days");
                break;
            case 12:
                System.out.println("31 days");
                break;
            default:
                System.out.println("Enter appropriate month");
        }
    }
}
```
## OUTPUT:
![image](https://github.com/swethamohanraj/EXPERIMENT-03/assets/94228215/c9c1badd-69fe-4f3b-bccf-85125b81cc5b)

## RESULT:
Hence, the number of days in a month was found by using java programming language.
