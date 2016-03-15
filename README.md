# Abhinav_JavaAssignment1_4
Days in month
import java.util.Scanner;
public class Month {
	public static void main(String[] args) {
		int days;
        Scanner monthscan= new Scanner(System.in);
        System.out.println("Hello User! Enter your month");
        int month = monthscan.nextInt();
        switch (month) {
            case 1:  days = 31;
                     break;
            case 2:  days = 28;
                     break;
            case 3:  days = 31;
                     break;
            case 4:  days = 30;
                     break;
            case 5:  days = 31;
                     break;
            case 6:  days = 30;
                     break;
            case 7:  days = 31;
                     break;
            case 8:  days = 31;
                     break;
            case 9:  days = 30;
                     break;
            case 10: days = 31;
                     break;
            case 11: days = 30;
                     break;
            case 12: days = 31;
                     break;
            default: days = 0;
                     break;
        }
        System.out.println("The days in Month number "+month+" are "+days);
    }
}

