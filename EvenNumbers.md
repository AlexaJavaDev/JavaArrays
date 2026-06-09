**Что делает:**
Выводит только чётные числа из массива.

**Код:**
```java
public class EvenNumbers {
    public static void main(String[] args) {
        int[] num = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        System.out.println(printEven(num));
    }

    public static String printEven(int[] num) {
        String numbers = "";
        for (int i = 0; i < num.length; i++) {
            if (num[i] % 2 == 0) {
                numbers += num[i] + " ";
            }
        }
        return numbers;
    }
}
```

## Пример вывода в консоли:
2 4 6 8 10
