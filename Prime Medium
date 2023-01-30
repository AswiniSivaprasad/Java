import java.util.Scanner;
 
class part1 extends Thread {
    public synchronized void run()
    {
     try
     {
    Scanner sc = new Scanner(System.in);
    System.out.print("Enter the number: ");
    int num=sc.nextInt();
    boolean flag = false;
    for (int i = 2; i <= num / 2; ++i) {
      // condition for nonprime number
      if (num % i == 0) {
        flag = true;
        break;
      }
    }

    if (!flag)
      System.out.println(num + " is a prime number.");
    else
      System.out.println(num + " is not a prime number.");
     }
     catch(Exception e)
     {
     System.out.println(" enter valid");
     }  
       
  }
}
class primehard {
    public static void main(String args[])
    {
        part1 t1 = new part1();
        Thread m1 = new Thread(t1);
       
        // start() method starts the execution of thread.
        m1.start();
        
        
       
    }
}
