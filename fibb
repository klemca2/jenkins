import java.util.Scanner;

public class fibonacci {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the number: ");
        int num = scanner.nextInt();
        scanner.close();
        
        int sum = 0;
        int a = 0;
        int b = 1;
        
        System.out.print("Fibonacci Series: ");
        for (int i = 1; i <= num; i++) {
            System.out.print(a + " ");
            sum += a;
            int temp = a;
            a = b;
            b = temp + b;
        }
        
        System.out.println("\nSum of Fibonacci Series: " + sum);
    }
}
