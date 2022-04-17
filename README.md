# Java

### Strings


  <details>
  <summary>Codes</summary>

   ```
  
  Strings in Java are Objects that are backed internally by a char array. Since arrays are
  immutable(cannot grow), Strings are immutable as well. Whenever a change to a String is made,
  an entirely new String is created. 
 
    
    public class Application
    {
    public static void main(String[] args)
    {
    int myInt = 7;
    
    String text = "Hello";
    String blank ="";
    String name = "Bob";
    
    String greeting = text +\blank + name;
    System.out.println(greeting);
    System.out.println("Hello"+" " + "Bob");
    System.out.println("My integer is: " + myInt);
    double myDouble = 7.8;
    System.out.println("My number is: " +my Double + ".");
    
    }
    }
    
  ```  
  </details>
  
  
### While loop
 
 <details>
 <summary>Codes</summary>
  
  ```
  
  public class Application{
  public static void main(String[] args){
  int value = 10;
  boolean loop= 4 < 5;
                      while( value<10){
  
                      System.out.println("Hello" + value);
  /*if(loop==5){
  break;
  }*/
  value=value+1;
                      
    
   }
  }
  
  ```
 </details>
 
  
 ### For Loops
  
  <details>
  <summary>Codes</summary>
  
  ```
  
  public class Application{
  public static void main(String[] args){
  for(int i=0; i<5; i++){
                    System.out.print("The value of i is: %d\n", i);
                    }
               }
          }
                    
  ```
 </details>
  
  
 ### Conditional Statements
  
  <details>
  <summary>Codes</summary>
    
   ```
    
    public class Application{
    public static void main(String[] args){
    int myInt=20;
    
    if(myInt<30){
    System.out.println("Yes, It's true!");
                  else{
    System.out.println("No, it's false!");
                  }
                  
    }
  }
                  
  ```
  </details>  
  
    
### Else If    
   
<details>
<summary>Codes</summary>
  
 ```
  
    public class Application{
    public static void main(String[] args){
    int myInt=5;
    
    if(myInt<10){
    System.out.println("Yes, It's true!");
                  else if(myInt<20){
    System.out.println("No, it's false!");
                  }
                  
    }
  }
  
                                     
  ```
  </details>
    
  
 ### If ElseIf Else
    
<details>
<summary>Codes</summary>  
  
```
    
 public class Application{
 public static void main(String[] args){
 int myInt=5;
    
 if(myInt<10){
    System.out.println("Yes, It's true!");
                  else if(myInt<20){
    System.out.println("No, it's false!");
                  }
       else{
    System.out.println("None of the above!");
                  }           
      }
    }  
                                     
  ```
 </details>
    
    
### Getting User-Input
  
  <details>
  <summary>Codes</summary>
    
  ```
    
    import java.until.Scanner;
    
    public class Application{
    public static void main(String[] args){
    //Create scanner object
    Scanner input=new Scanner(System.in);
    
    //Output the program
    System.out.println("Enter the integer/float/double/char/string: ");
    
    //Wait for the user to enter something
    int/float/double/char/string value = input.nextInt/Float/Double/Char/String();
    
    //Tell then what they entered
    System.out.println("You Entered: " + line/value);
    
    }
    }
    
    
  ```
  </details>
    
  
### Do while loop
  
  <details>
  <summary>Codes </summary>
    
  ```
    
    import java.until.Scanner;
    
    public class App{
    public static void main(String[] args){
    
    Scanner scanner = new Scanner(System.in):
    /*
    System.out.println("Enter a number: ");
    int value = scanner.nextInt();
    
    while(value i=5){
    System.out.println("Enter a number: ");
    value = scanner.nextInt();
    }*/
    
    int value=0;
    do {
    System.out.println("Enter a number: ");
    value = scanner.nextInt();
    }
    while(value !=5);
    
    System.out.println("got 5!");
    
    }
    }
    
  ```
  </details>
    
    
### Switch
    
<details>
<summary>Codes</summary>
    
 ```   
    
    import java.until.Scanner;
    public class Application{
    
    public static void main(String[] args){
    Scanner input = new Scanner(System.in);
    
    System.out.println("Please enter a command: ");
    String text = input.nextLine();
    
    switch(text){
    case "start";
    System.out.println("Machine Started!");
    break;
    
    case "stop";
    System.out.println("Machine Stopped!");
    break;
    
    default:
    System.out.println("Command not recognized!");
    }
    }
    }
    
    
  ```
  </details>
    
    
 ### Arrays
   
  <details>
  <summary>Codes</summary>
     
  ```
     
     public class App{
     public static void main(String[] args){
     int value = 7;
     int[] values;
     values = new int[3];
     
     System.out.println(values[0]);
     
     values[0] = 10;
     values[1] = 20;
     values[2] = 30;
     
     System.out.println(values[0]);
     System.out.println(values[1]);
     System.out.println(values[2]);
     
     for(int i=0; i<values.length; i++){
             System.out.println(values[i]);
     }
     int[] numbers = {5, 6, 7};
     for(int i=0; i<numbers.length; i++){
     System.out.println(number[i]);
     }
     }
     }
     
     
  ```
 </details>
    
     
    
 ### Arrays of Strings
 
  <details>
  <summary>Codes</summary>
      
  ``` 
      
      public class App {
      public static void main(String[] args){
      String[] words = new String[3];
      
      words[0] = "Hello";
      words[1] = "to";
      words[2] = "you";
      
      System.out.println(words[2]);
      String[] fruits = {"apple", "banana", "pear", "kiwi");;
      
      for(String fruit: fruits){
      System.out.println(fruit);
      }
      int value = 0;
      String text = null;
      System.out.println(text);
      String[] texts = new String[2];
      System.out.println(texts[0]);
      texts[0] = "one";
      }
      }
      
      
 ``` 
 </details>
    
 ### Multi Dimensional Array 
   
   <details>
   <summary>Codes</summary>
     
   ```
      public class App{
      public static void main(String[] arrgs){
      int value = {3, 5,254};
      System.out.println(values[2]);
      int[][]grid = {
        {3, 5, 2343}
        {2, 4}
        {1, 2, 3, 4}
     };
     
     System.out.println(grid[1][1]);
     System.out.println(grid[0][2]);
     
     String[][] = text= new String[2][3];
     
     text[0][1] = "Hello there";
     System.out.println(text[0][1]);
     
     for(int row=0; row<grid.length; row++){
             for(int col=0; col<grid[row].length;col++){
     System.out.println(grid[row][col] + "\t");
     }
     System.out.println();
     }
     String[][] words = new String[2][];
     System.out.println(words[0]);
     words[0] = new String[3];
     words[0] = "Hi there";
     System.out.println(words[0][1]);
     }
     }
     
   ```
     
  </details>
    
 ### Classes and Objects
    
    
     Class is a template for creating objects or class is a blueprint if you like for creating        objects.
     Classes can contain
     1. Data(Instance Variables)
     2. Subroutines(Methods)
     Object is an instance of class.
    
  <details>  
  <summary>Codes</summary>
      
   ```
      
      class Person{
      String name;
      int age;
      }
      
      public class App{
      public static void main(String[] args){
      Person person1 = new Person();
      person1.name = "Joe";
      person1.age = "21";
      
      Person person2 = new Person();
      person2.name = "Ally";
      person2.age + "33";
      
      System.out.println(person1.name);
      
      }
      }
    
    Output:
    Joe
      
  ```
      
  </details>
    
  
### Methods
    
  <details>
  <summary>Codes</summary>
      
  ```
    
     class Person{
     String name;
     int age;
      
     void speak(){
     for(int i=o; i<3; i++){
                        System.out.println("My name is: " + name + "and I am" + age+ " years old ");
     void sayHello() {
                        System.out.println("Hello there!");
         }
     }
      
     public class App{
     public static void main(String[] args){
     Person person1 = new Person();
     person1.name = "Joe";
     person1.age = "21";
      
     Person person2 = new Person();
     person2.name = "Ally";
     person2.age + "33";
      
     System.out.println(person1.name);
      
     }
     }
 
   ```
      
   </details>
      
 
### Getters and Returns
    
  <details>
  <summary>Codes</summary>
    
  ```
    class Person{
    String name;
    int age;
    
    void speak(){
    System.out.println("My name is: " +name);
    }
    
    int calculateYearsToRetirement(){
    int yearsLeft = 65-age;
    System.out.println(yaersLeft);
    return yearsLeft;
    
    }
    }
    
    public class App {
    
    
    public static void main(String[] args){
    Person person1 = new Person();
    
    person1.name ="Joe";
    person1.age="25";
    
    
    
    
  
