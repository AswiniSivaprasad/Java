import java.util.Scanner;

public class empbonus {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the grade of the employee (A or B): ");
        char grade = scanner.next().charAt(0);
        System.out.print("Enter the employee salary: ");
        double salary = scanner.nextDouble();

        double bonus = 0;
        if (grade == 'A'||grade=='a') {
            bonus = 0.05 * salary;
        } else if (grade == 'B'||grade=='b') {
            bonus = 0.1 * salary;
        }

        if (salary < 10000) {
            bonus += 0.02 * salary;
        }

        double totalSalary = salary + bonus;
        System.out.println("Salary=" + salary);
        System.out.println("Bonus=" + bonus);
        System.out.println("Total to be paid:" + totalSalary);
    }
}
