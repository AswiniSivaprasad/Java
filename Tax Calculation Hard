import java.util.Scanner;

public class taxcal{

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Enter the income: ");
        double income = input.nextDouble();
        
        double taxableIncome = income - 250000;
        double tax = 0;
        
        if (taxableIncome <= 0) {
            System.out.println("No tax");
        } else if (taxableIncome <= 250000) {
            tax = taxableIncome * 0.1;
        } else if (taxableIncome <= 500000) {
            tax = 25000 + (taxableIncome - 250000) * 0.2;
        } else {
            tax = 75000 + (taxableIncome - 500000) * 0.3;
        }
        
        System.out.println("Taxable Income: " + taxableIncome);
        System.out.println("Tax= " + tax);
    }

}
