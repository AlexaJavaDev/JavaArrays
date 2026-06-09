**Что делает:**  
Считает среднее арифметическое элементов массива.

**Код:**
```java
public class AverageArray {
    public static void main(String[] args) {
        int[] str = {1, 2, 3, 4, 5};
        System.out.println("Среднее: " + average(str));
    }

    public static double average(int[] str) {
        int sum = 0;  // начинаем с 0
        for (int i = 0; i < str.length; i++) {
            sum += str[i];  // добавляем каждый элемент к сумме
        }
        // (double) — превращаем сумму в дробное число, чтобы деление было точным
        return (double) sum / str.length;
    }
}
```
## Пример вывода в консоли:
```
Среднее: 3.0
```
