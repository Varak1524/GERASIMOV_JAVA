import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        // Ввод чисел
        System.out.print("Введите первое число (a): ");
        int a = scanner.nextInt();
        
        System.out.print("Введите второе число (b): ");
        int b = scanner.nextInt();
        
        // Сравнение чисел
        if (a > b) {
            System.out.println("a > b");
        } else if (a < b) {
            System.out.println("a < b");
        } else {
            System.out.println("a = b");
        }
        
        // Операции с числами
        System.out.println("Сложение: " + (a + b));
        System.out.println("Вычитание: " + (a - b));
        System.out.println("Умножение: " + (a * b));
        if (b != 0) {
            System.out.println("Деление: " + (a / (double)b));
        } else {
            System.out.println("Деление на ноль невозможно");
        }
    }
}




import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        // Ввод строк
        System.out.print("Введите первую строку (a): ");
        String a = scanner.nextLine();
        
        System.out.print("Введите вторую строку (b): ");
        String b = scanner.nextLine();
        
        // Сравнение строк
        if (a.equals(b)) {
            System.out.println("Строки идентичны");
        } else {
            System.out.println("Строки неидентичны");
        }
    }
}



public class Main {
    public static void main(String[] args) {
        int[] numbers = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        
        System.out.println("Четные числа из массива:");
        for (int num : numbers) {
            if (num % 2 == 0) {
                System.out.println(num);
            }
        }
    }
}
