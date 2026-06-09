**Что делает:**  
Выводит каждое слово из массива и его длину.

**Код:**
```java
public class WordLength {
    public static void main(String[] args) {
        String[] str = {"apple", "banana", "cherry"};
        String res = "";

        for (int i = 0; i < str.length; i++) {
            res += str[i] + ": " + str[i].length() + "\n";
        }
        System.out.println(res);
    }
}
```
## Пример вывода в консоли:
```
apple: 5
banana: 6
cherry: 6
```
