# JavaLab
## 2a)experiment


```java
class MyClass {

    void displayMessage() {
        System.out.println("Welcome to Java");
    }

    int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {

        MyClass obj = new MyClass();

        obj.displayMessage();

        int result = obj.add(10, 20);
        System.out.println("Sum: " + result);
    }
}

```
## output


<img width="897" height="234" alt="Screenshot 2026-01-02 093417" src="https://github.com/user-attachments/assets/24dc33ce-b383-4aab-9413-35673acdfd3c" />




## 2b)experiment

---java
class OverloadExample {

    int add(int a, int b) {
        return a + b;
    }

    double add(double a, double b) {
        return a + b;
    }

    int add(int a, int b, int c) {
        return a + b + c;
    }

    public static void main(String[] args) {

        OverloadExample obj = new OverloadExample();

        System.out.println("Result of adding two integers: " + obj.add(10, 20));
        System.out.println("Result of adding two double values: " + obj.add(5.5, 4.5));
        System.out.println("Result of adding three integers: " + obj.add(1, 2, 3));
    }
}

---

## output

<img width="966" height="236" alt="Screenshot 2026-01-02 093431" src="https://github.com/user-attachments/assets/06c6254e-6256-42c4-97bf-a313928538dd" />


## 2c)experiment

---java 
class Student {

    String name;
    int age;
    int marks;

    Student(String n, int a, int m) {
        name = n;
        age = a;
        marks = m;
    }

    void display() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Marks: " + marks);
    }

    public static void main(String[] args) {

        Student s1 = new Student("Alice", 20, 85);
        s1.display();
    }
}

---

## output


<img width="910" height="239" alt="Screenshot 2026-01-02 093443" src="https://github.com/user-attachments/assets/8b6ff475-b229-48b0-91aa-5b40a4657413" />
