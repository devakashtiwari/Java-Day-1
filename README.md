
---

## 📌 Java “Hello, World!” Program – Line by Line Explanation

```java
public class Hello {
```

* `public` → Makes the class accessible from anywhere.
* `class` → Keyword used to define a class in Java.
* `Hello` → Name of the class.
  ⚠️ **Rule:** The class name must match the file name (`Hello.java`).

---

```java
    public static void main(String[] args) {
```

* `public` → Allows the JVM to access this method.
* `static` → Enables the method to run without creating an object of the class.
* `void` → Indicates the method does not return any value.
* `main` → Entry point of the Java program (execution starts here).
* `String[] args` → Command-line arguments passed to the program.

---

```java
        System.out.println("Hello, World!");
```

* `System` → A built-in Java class.
* `out` → Output stream connected to the console.
* `println()` → Prints text to the console and moves to a new line.
* `"Hello, World!"` → The message displayed on the screen.

---

```java
    }
```

* Closes the `main` method.

---

```java
}
```

* Closes the `Hello` class.

---

## ✅ Output

```
Hello, World!
```

---


