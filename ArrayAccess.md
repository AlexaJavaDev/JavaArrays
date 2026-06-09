**Что делает:**  
Доступ к элементам массива: первый элемент и последний элемент.

**Код:**
```java
public class ArrayAccess {
    public static void main(String[] args) {
        // Доступ к элементу по индексу
        String[] str = {"java", "python", "c++"};
        System.out.println(str[0]);  // первый элемент

        // Последний элемент через length - 1
        int[] a = {10, 20, 30, 40, 50};
        System.out.println(a[a.length - 1]);
    }
}
```
## Пример вывода в консоли:
```
java
50
```
