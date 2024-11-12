import java.util.Scanner;

public class RecursionExample {

    // Recursive method to calculate factorial
    public static int factorial(int n) {
        // Base case: If n is 0 or 1, return 1 (since 0! = 1! = 1)
        if (n == 0 || n == 1) {
            return 1;
        } else {
            // Recursive case: n * factorial of (n - 1)
            return n * factorial(n - 1);
        }
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter a number to calculate its factorial: ");
        int number = scanner.nextInt();
        
        // Call the recursive factorial method
        int result = factorial(number);
        
        System.out.println("Factorial of " + number + " is: " + result);
        
        scanner.close();
    }
}
