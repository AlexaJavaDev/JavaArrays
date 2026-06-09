**Что делает:**  
Выводит только те слова, длина которых больше 4 символов.
**Код:**

```java
public class WordsLength {
    public static void main(String[] args) {
        String[] str = {"Hello", "World", "Java", "Code"};
        System.out.println(filterWordsLength(str));
    }

    public static String filterWordsLength(String[] str) {
        String res = "";
        for (int i = 0; i < str.length; i++) {
            if (str[i].length() > 4) {
                res += str[i] + "\n";
            }
        }
        return res;
    }
}
```
## Пример вывода в консоли:
```
Hello
World
```
