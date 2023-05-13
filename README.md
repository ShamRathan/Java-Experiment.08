# Java-Experiment.5
# Inheritance

## Aim:
  To write a Java program using inheritance one class can acquire the properties of others.
  
## Algorithm:

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Animal" and create required statements.

Step 3 : Create a another class called "Bird" and create required statements.

Step 3 : Create another class,called the Solution Class.

Step 4 : Using the 'extends' keyword you can inherit classes, do the same with above created class.

Step 5 : Display the statements from the first and secomd Class using Solution Class in the terminal.

## Program:
```
Developed by: S.Sham Rathan
Register.no : 212221230093

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
## Output:
![image](https://github.com/ShamRathan/Java-Experiment.5/assets/93587823/1bd6f921-574d-4da1-b063-6b53b96fcd63)


## Result 
  We have successfully created a Java program using inheritance one class can acquire the properties of others.
