import java.util.Scanner;

public class TimeConverter {
  public static void main(String[] args) {
    Scanner kb = new Scanner(System.in); 
    System.out.print("Enter a number of seconds: ");
    int seconds = kb.nextInt();
    {
    	 System.out.println(seconds + " is equal to");
    }
    int minutes = 0;
    int hours = 0;
    int days = 0;

   
    if (seconds >= 86400) {
      days = seconds / 86400; 
      seconds -= days * 86400; 
    }
   
    if (seconds >= 3600) {
      hours = seconds / 3600; 
      seconds -= hours * 3600; 
    }
   
    if (seconds >= 60) {
      minutes = seconds / 60; 
      seconds -= minutes * 60; 
    }

  
    System.out.println(days + " day(s)");
    
    System.out.println(hours + " hour(s)");
    
    System.out.println(minutes + " minute(s)");
   
    System.out.println(seconds + " second(s)");
  kb.close();
  }
}
