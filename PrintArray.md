**Что делает:**  
Выводит все элементы массива через цикл, каждый с новой строки.

**Код:**
```java
public class PrintArray {
    public static void main(String[] args) {
        String[] str = {"Anna", "Ivan", "Olga"};
        String res = "";

        for (int i = 0; i < str.length; i++) {
            res += str[i] + "\n";
        }
        System.out.println(res);
    }
}
```

## Пример вывода в консоли:
```
Anna
Ivan
Olga
```
