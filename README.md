# Class-and-object-instance-
Class and Object Instance

class Person {
    String name;
    int age;

    public void display() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }
}

public class ClassAndObject {
    public static void main(String[] args) {
        Person person = new Person();
        person.name = "Alice";
        person.age = 25;
        person.display();
    }
}

Output

Name: Alice  
Age: 25
