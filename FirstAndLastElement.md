**Что делает:**  
Выводит первый и последний элемент массива строк через пробел.

**Код:**
```java
public class FirstAndLastElement {
    public static void main(String[] args) {
        String[] str = {"Hello", "World", "Java"};
        System.out.println(massiv(str));
    }

    public static String massiv(String[] str) {
        return str[0] + " " + str[str.length - 1];
    }
}
```
#### Пример вывода в консоли:
```
Hello Java
```

---

#### Мои заметки:
- `str[0]` — первый элемент
- `str[str.length - 1]` — последний элемент (длина массива минус 1)
- Соединяем их через пробел
