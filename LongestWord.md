**Что делает:**  
Находит самое длинное слово в массиве строк.

**Код:**
```java
public class LongestWord {
    public static void main(String[] args) {
        String[] str = {"Java", "Python", "C++", "JavaScript"};
        System.out.println(massiv(str));
    }

    public static String massiv(String[] str) {
        String longest = str[0];

        for (int i = 0; i < str.length; i++) {
            if (str[i].length() > longest.length())
                longest = str[i];
        }
        return longest;
    }
}
```
#### Пример вывода в консоли:
```
JavaScript
```

---

#### Мои заметки:
- `longest` — переменная, которая хранит самое длинное слово на данный момент
- В цикле сравниваем длину текущего слова с длиной `longest`
- Если текущее слово длиннее — обновляем `longest`
