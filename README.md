# Switch-Case
import java.util.Scanner;
public class SwitchCase {
     public static void main(String[] args) {
     Scanner input = new Scanner(System.in);
     System.out.println("Choose your role out of these options:\n Option1: Administrator\n Option2: Faculty\n Option3: Staff\n Option4: Student\n Option5: Guest\n Enter 1 for Option1 2 for Option2 3 for Option3 4 for Option4 5 for Option5");
     int option = input.nextInt();
     switch (option) {
     case 1:
       System.out.println("Welcome Administrator!");
       break;
     case 2:
       System.out.println("Welcome Faculty!");
       break;
     case 3:
       System.out.println("Welcome Staff!");
       break;
     case 4:
       System.out.println("Welcome Student!");
       break;
     case 5:
       System.out.println("Welcome Guest!");
       break;
     default:
       System.out.println("Please choose one of these options");
}
}
 }
