```
import java.util.Scanner;

public class MinutesConversion {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the number of minutes: ");
        double minutes = scanner.nextDouble();
        double hours = minutes / 60;
        double days = minutes / 1440;
        System.out.println(minutes + " minutes equals " + hours + " hours");
        System.out.println(minutes + " minutes equals " + days + " days");
        scanner.close();
    }
}
```
