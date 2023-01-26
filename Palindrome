import java.util.*;
import java.util.Scanner;
class palindrome {
public static void main(String[] args)
{
            Scanner input=new Scanner(System.in);
            System.out.print("Enter the string:");
            String value=input.next();
      try
      {
            int num=Integer.parseInt(value);
            int rev=0,rem,num2=num;
            while(num!=0){
            rem=num%10;
            rev=rev*10+rem;
            num=num/10;
            }
            if(num2==rev)
            System.out.println("The number is palindrome");
            else
            System.out.println("The number is not palindrome");
            }
            catch(Exception e){
            StringBuffer s1=new StringBuffer(value);
            s1.reverse();
            String s2=s1.toString();
            if(value.equals(s2))
            System.out.println("The strings are palindrome");
            else
            System.out.println("The strings are not palindrome");
      }
}}
