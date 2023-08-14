
import java.util.*;
public class LeapYear {
public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter a Year");
    int b = sc.nextInt();
    boolean x = b%4 == 0;
    boolean y = (b%100) != 0;
    boolean z = (b%100 == 0) && (b%400 == 0);
    if(x && (y||z)){
    System.out.println("leap year");
    }
    else{
        System.out.println("not leap year");
    }

}    
}
