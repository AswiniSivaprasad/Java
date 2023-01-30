import java.util.Scanner;
class palindrome {
static int reverseNumber(int number)
{
     int reverse = 0;
     int rem = 0;
     while(number !=0)
     {
         rem = number % 10;
         reverse = (reverse*10) + rem;
         number = number/10;
     }
      
     return reverse;
  }
  static boolean checkpalindrome(int number)
  {
       int reverse = reverseNumber(number);
       if(reverse == number)
       {
            return true;
       }
       else
       {
          return false;
       }
   }
   static void reverseAndAdd(int number)
   {
         if(checkpalindrome(number))
         {
              System.out.println("Given Number is already a palindrome");
         }
         else
         {
              while (!checkpalindrome(number))
              {
                  int reverse = reverseNumber(number);
                  int sum = number + reverse;
                  System.out.println(number+" + "+reverse+" = "+sum);
                  number = sum;
               }
           }
     }
     public static void main(String[] args)
     {
          Scanner sc = new Scanner(System.in);
          System.out.print("Enter Number : ");
          int inputNumber=sc.nextInt();
          reverseAndAdd(inputNumber);
     }
}
