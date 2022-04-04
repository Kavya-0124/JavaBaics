# StringsinJava


  <details>
  Strings in Java are Objects that are backed internally by a char array. Since arrays are
  immutable(cannot grow), Strings are immutable as well. Whenever a change to a String is made,
  an entirely new String is created. 
  <summary> Codes </summary>


    ~~~
    
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
    
    ~~~
    
    
 
  </details>
  
  
  ### While loop
 
 <summary>Codes</summary>
 <details>
  
 ~~~
  
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
  
  ~~~
  
  </details>
  
  ### For Loops
  
  <details>Codes</details>
  <summary>
  
  ~~~
  
  public class Application{
  public static void main(String[] args){
  for(int i=0; i<5; i++){
                    System.out.print("The value of i is: %d\n", i);
                    }
               }
          }
                    
  ~~~
                    
 </summary>
  
  
  ### Conditional Statements
  
  <details>Codes</details>
  
  <summary>
    
    ~~~
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
  
   ### Else If               
  
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
    
    ### If-ElseIf-Else
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
                                     
  ~~~
  </summary>
    
