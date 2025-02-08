import java.util.Scanner;

public class HotelAdvikaMenu {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("Welcome to Hotel Advika");
        System.out.println("Press 1 for Breakfast...");
        System.out.println("Press 2 for Lunch...");
        System.out.println("Press 3 for Dinner...");
        System.out.println("Press 4 for Snacks...");
        System.out.println("Press 5 for Cold drinks and Soft drinks...");
      

        int choice = s.nextInt();

        switch (choice) {
            case 1:

                System.out.println("Press 1 for Poha...");
                System.out.println("Press 2 for Idli-Sambhar");
                System.out.println("Press 3 for Sheera and Upma");
                System.out.println("Press 4 for Masala Chai...");
                int choice1 = s.nextInt();
                switch (choice1)
                 {
                    case 1: System.out.println("Poha is getting ready...."); 
                    break;
                    case 2: System.out.println("Idli-Sambhar getting ready..."); 
                    break;
                    case 3: System.out.println("Sheera and Upma getting ready..."); 
                    break;
                    case 4: System.out.println("Masala Chai getting ready..."); 
                    break;
                    default: System.out.println("Please select the correct option.");
                }
                break;

            case 2:

                System.out.println("Press 1 for Chapati-Bhaji");
                System.out.println("Press 2 for Bhurji Pav");
                System.out.println("Press 3 for Daal Khichdi");
                System.out.println("Press 4 for Vada Pav");
                int choice2 = s.nextInt();
                switch (choice2)
                 {
                    case 1: System.out.println("Chapati-Bhaji getting ready...");
                     break;
                    case 2: System.out.println("Bhurji Pav getting ready..."); 
                    break;
                    case 3: System.out.println("Daal Khichdi getting ready..."); 
                    break;
                    case 4: System.out.println("Vada Pav getting ready..."); 
                    break;
                    default: System.out.println("Please enter the correct option.");
                }
                break;

            case 3:

                System.out.println("Press 1 for Chicken Biryani");
                System.out.println("Press 2 for Chicken Thali");
                System.out.println("Press 3 for Kolhapuri Thali");
                System.out.println("Press 4 for Rice Plate");
                int choice3 = s.nextInt();
                switch (choice3)
                 {
                    case 1: System.out.println("Chicken Biryani getting ready..."); 
                    break;
                    case 2: System.out.println("Chicken Thali getting ready..."); 
                    break;
                    case 3: System.out.println("Kolhapuri Thali getting ready..."); 
                    break;
                    case 4: System.out.println("Rice Plate getting ready...");
                     break;
                    default: System.out.println("Please select the correct option.");
                }
                break;

            case 4:

                System.out.println("Press 1 for Veg Manchurian");
                System.out.println("Press 2 for Noodles");
                System.out.println("Press 3 for Maggi");
                System.out.println("Press 4 for Chicken Lollipop");
                int choice4 = s.nextInt();
                switch (choice4) 
                {
                    case 1: System.out.println("Veg Manchurian getting ready..."); 
                    break;
                    case 2: System.out.println("Noodles getting ready..."); 
                    break;
                    case 3: System.out.println("Maggi getting ready...");
                     break;
                    case 4: System.out.println("Chicken Lollipop getting ready..."); 
                    break;
                    default: System.out.println("Please select the correct option.");
                }
                break;

            case 5:

                System.out.println("Press 1 for Soda");
                System.out.println("Press 2 for Coca-Cola");
                System.out.println("Press 3 for Ice Cream");
                System.out.println("Press 4 for Pan");
                int choice5 = s.nextInt();
                switch (choice5) 
                {
                    case 1: System.out.println("Soda is available.");
                     break;
                    case 2: System.out.println("Coca-Cola is available."); 
                    break;
                    case 3: System.out.println("Ice Cream is available."); 
                    break;
                    case 4: System.out.println("Pan is available."); 
                    break;
                    default: System.out.println("Please select the correct option.");
                }
                break;

            default:
                System.out.println("Invalid choice! Please select a valid option.");
        }
        s.close();
    }
}
