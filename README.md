## Java-Ex-08
### Using Inheritance one class can acquire the properties of others.
## Aim:-
To write a Java program using inheritance one class can acquire the properties of others.

## Algorithm:-
### Step 1 : 
Open Intelli J application or any other code editor.

### Step 2 : 
Create a class called "Animal" and create required statements.

### Step 3 : 
Create a another class called "Bird" and create required statements.

### Step 3 : 
Create another class,called the Solution Class.

### Step 4 : 
Using the 'extends' keyword you can inherit classes, do the same with above created class.

### Step 5 : 
Display the statements from the first and second Class using Solution Class in the terminal.

## Program:-
```java
class Animal{
void walk(){
System.out.println("I am walking");
  }
}

class Bird extends Animal{
void fly(){
System.out.println("I am flying");
  }
}

public class Solution{
public static void main(String args[]){
Bird bird = new Bird();
bird.walk();
bird.fly();
  }
}
```
## Output:-
![image](https://github.com/Kirupanandhan/Write-a-program-to-add-retrieve-and-remove-the-element-from-the-ArrayList/assets/94386222/84f21e4d-ca53-47d2-871a-12908bd60d01)

## Result:-
We have successfully created a Java program using inheritance one class can acquire the properties of others.
