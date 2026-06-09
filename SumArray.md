**Что делает:**  
Считает сумму всех элементов массива.

**Код:**
```java
public class SumArray {
    public static void main(String[] args) {
        int[] a = {5, 12, 8, 21, 3};
        int sum = 0;

        for (int i = 0; i < a.length; i++) {
            sum += a[i];
        }
        System.out.println(sum);
    }
}
```

## Пример вывода в консоли:
```
49
```
