**Что делает:**  
Находит самое большое и самое маленькое число в массиве.

---

### Вариант 1: MIN

**Код:**
```java
public class FindMin {
    public static void main(String[] args) {
        int[] num = {3, 7, 2, 9, 4};
        System.out.println(massiv(num));
    }

    public static int massiv(int[] num) {
        int min = num[0];
        for (int i = 0; i < num.length; i++) {
            if (num[i] < min)
                min = num[i];
        }
        return min;
    }
}
```

## Пример вывода в консоли:
```
2
```

---

### Вариант 2: MAX

**Код:**
```java
public class FindMax {
    public static void main(String[] args) {
        int[] num = {3, 7, 2, 9, 4};
        System.out.println(massiv(num));
    }

    public static int massiv(int[] num) {
        int max = num[0];
        for (int i = 0; i < num.length; i++) {
            if (num[i] > max)
                max = num[i];
        }
        return max;
    }
}
```

## Пример вывода в консоли:
```
9
```
