// Java program for the above approach
import java.util.Scanner;
 
public class GFG {
    public static void
    guessingNumberGame()
    {
        Scanner sc = new Scanner(System.in);
        int num = 1 + (int)(100* Math.random());
        int Kmc = 5;
 
        int tk, guessed_number;
 
        System.out.println( "choose a number between 1 to 100 within 5 trials!!!!");
        for (tk = 0; tk < Kmc; tk++) {
            System.out.println("Guess the number:");
            guessed_number = sc.nextInt();
            if (num == guessed_number) {
                System.out.println(
                    "Congratulations!!!!! You guessed the number.");
                break;
            }
            else if (num > guessed_number
                     && tk != Kmc - 1) {
                System.out.println(
                    "The number is greater than the " + guessed_number);
            }
            else if (num < guessed_number
                     && tk != Kmc - 1) {
                System.out.println(
                    "The number is less than the " + guessed_number);
            }
        }
 
        if (tk == Kmc) {
            System.out.println(
                "Your trails are completed.sorry..!!");
 
            System.out.println(
                "The number is " + num);
        }
    }
 
    public static void
    main(String arg[])
    {
        guessingNumberGame();
    }
}
