**Что делает:**  
Перемножает все элементы массива (вычисляет произведение).

**Код:**
```java
public class ProductOfArray {
    public static void main(String[] args) {
        int[] str = {1, 2, 3, 4, 5};
        System.out.println(massiv(str));
    }

    public static int massiv(int[] str) {
        int res = 1;

        for (int i = 0; i < str.length; i++) {
            res *= str[i];
        }
        return res;
    }
}
```
#### Пример вывода в консоли:
```
120
```

---

#### Мои заметки:
- Для суммы мы начинали с `0`, а для произведения — с `1` (умножение на 0 обнулит всё!)
- `res *= str[i]` — то же самое, что `res = res * str[i]`
- 1 × 2 × 3 × 4 × 5 = 120
