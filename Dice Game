import java.util.Random;
import java.util.Scanner;

public class DiceGame {
  public static void main(String[] args) {
    Scanner kb = new Scanner(System.in);
    
    int rolled = rollDice();
    
    System.out.println("I have two dice. Please guess the result of a roll.");
    System.out.println("Enter your guess, It will be between 2 and 12: "); 
    int guess = kb.nextInt();
    
    kb.close();
    
    if (checkGuess(guess, rolled)) {
      System.out.println("You guessed it! The number was " + rolled);
    } else {
      System.out.println("Sorry, you were wrong. The number was " + rolled);
    }
  }
 
  public static int rollDice() {
    
    Random random = new Random();
    

    int die1 = random.nextInt(6) + 1;
    int die2 = random.nextInt(6) + 1;
    
   
    return die1 + die2;
  }
  
  
  public static boolean checkGuess(int guess, int rolled) {
   
    return guess == rolled;

  }
}
