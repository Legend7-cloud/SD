import java.util.Scanner;
public class SD1 {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        //input temperature
        System.out.print("Enter temperature value: ");
        double inputTemp = scanner.nextDouble();
        scanner.nextLine(); 
        System.out.print("Enter the unit (C for Celsius, F for Fahrenheit, K for Kelvin): ");
        String unit = scanner.nextLine().trim().toUpperCase();
        //Calculation
        double celsius, fahrenheit, kelvin;
        try{
        switch (unit) {
            case "C":
                celsius = inputTemp;
                fahrenheit = (celsius * 9/5) + 32;
                kelvin = celsius + 273.15;
                System.out.println("Input: " + celsius + " °C");
                System.out.println("Fahrenheit: " + fahrenheit + " °F");
                System.out.println("Kelvin: " + kelvin + " K");
                break;
            case "F":
                fahrenheit = inputTemp;
                celsius = (fahrenheit - 32) * 5/9;
                kelvin = celsius + 273.15;
                System.out.println("Input: " + fahrenheit + " °F");
                System.out.println("Celsius: " + celsius + " °C");
                System.out.println("Kelvin: " + kelvin + " K");
                break;
            case "K":
                kelvin = inputTemp;
                celsius = kelvin - 273.15;
                fahrenheit = (celsius * 9/5) + 32;
                System.out.println("Input: " + kelvin + " K");
                System.out.println("Celsius: " + celsius + " °C");
                System.out.println("Fahrenheit: " + fahrenheit + " °F");
                break;
            default:
                System.out.println("Invalid unit. Please use C, F, or K.");
        }
        }
        finally{
        scanner.close();
        }
    }
}
