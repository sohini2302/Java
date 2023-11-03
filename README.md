import java.util.*;//Import Java Packages
class Square//Declare the class
{
    public static void main(String args[])//main method
    {
        Scanner sc= new Scanner(System.in);
        System.out.println("Enter the limits:");
        int n= sc.nextInt();
        int i=1;
        int c=0;
        do {
            c= c+(i*i);
            i= i+1;
        } while (i<= n);
        System.out.println("Sum of the squares of numbers upto "+n +":"+c);
        }//End of main
    }//End of class
