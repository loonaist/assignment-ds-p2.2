# assignment-ds-p2.2
import java.util.Random;
public class Q2class {
    
    public void number(){
        Random rnd = new Random();
        int tickets;
        System.out.print("The number of tickets the customer has is: ");
        tickets = 1 + rnd.nextInt(10);
        System.out.println(tickets);
    }
       
}
