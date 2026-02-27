import java.util.*;

public class Main{
    public static void main(String[] args){
        Scanner sc =new Scanner(System.in);
        ATM atm=new ATM();
        
        while(true){
        System.out.println("\n1.Deposite");
        System.out.println("2.Withdraw");
        System.out.println("3.Show Balance");
        System.out.println("4.Exit");
        System.out.print("\nEnter the choice: ");
        int choice=sc.nextInt();
        
            switch(choice){
            case 1:
                System.out.println("\nEnter the amount to be deposited: ");
                int depamo=sc.nextInt();
                atm.deposite(depamo);
                System.out.println("Amount added successfuly");
                break;
            case 2:
                System.out.println("\nEnter the amount to be withdraw: ");
                int withamo=sc.nextInt();
                atm.withdraw(withamo);
                System.out.println("Amount withdraw successfuly");
                break;
            case 3:
                System.out.println("Balance: "+atm.Balance());
                break;
            case 4:
                System.out.println("Exiting.....");
                System.out.println("ThankYou");
                sc.close();
                System.exit(0); //is used to completely stop the               Java program immediately.
            default:
                System.out.println("Invalid Choice");
                break;
        }
        
    }
        
    }
}
