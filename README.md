# StringsinJava


  <details>
  Strings in Java are Objects that are backed internally by a char array. Since arrays are
  immutable(cannot grow), Strings are immutable as well. Whenever a change to a String is made,
  an entirely new String is created. 
  <summary> Codes </summary>


    ```
    
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
 
 <summary>Codes</summary>
 <details>
  
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
  
  <details>Codes</details>
  <summary>
  
  ```
  
  public class Application{
  public static void main(String[] args){
  for(int i=0; i<5; i++){
                    System.out.print("The value of i is: %d\n", i);
                    }
               }
          }
                    
  ```
                    
 </summary>
  
  
  ### Conditional Statements
  
  <details>Codes</details>
  
<summary>
    
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
   </summary>  
  
   ### Else If    
   
   <summary>
    
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
   
  </summary>
  
 ### If ElseIf Else
  
  <summary>
    
 ```
    
 public class Application{
 public static void main(String[] args){
 f int myInt=5;
    
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
                                     
</summary>
    
### Getting User-Input
  
  <details>Codes</details>
  
  <summary>
    
    ```
    
    
    import java.until.Scanner;
    
    public class Application{
    public static void main(String[] args){
    //Create scanner object
    Scanner input=new Scanner(System.in);
    
    //Output the program
    System.out.println("Enter the integer/float/double/char/string: ");
    
    //Waut for the user to enter something
    int/float/double/char/string value = input.nextInt/Float/Double/Char/String();
    
    //Tell then what they entered
    System.out.println("You Entered: " + line/value);
    
    }
    }
    
    ```
    
  </summary>
  
  ### Do while loop
  
  <details>Codes</details>
  
  <summary>
    
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
    
  </summary>
    
