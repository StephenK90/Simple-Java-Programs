import java.util.Scanner;

public class Pennies_for_Pay {
  public static void main(String[] args) {
    Scanner kb = new Scanner(System.in);
    
   
    System.out.print("Enter the number of days worked: ");
    int days = kb.nextInt();
    

    if (days < 1) {
      System.out.println("Error: The number of days must be at least 1.");
      return;
    }
    
   
    double totalSalary = 0;
    

    double salary = 0.01;
    
 
    System.out.println("Day\tSalary");
    
    
    for (int i = 1; i <= days; i++) {
  
      System.out.println(i + "\t$" + salary);
      

      totalSalary += salary;
      

      salary *= 2;
    }
    

    System.out.printf("Total salary: $%.2f", totalSalary);
    kb.close();
  }
}
