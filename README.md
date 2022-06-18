# TrainInJava
This is for basic understanding of Java 


TODO : Create a program to accept a string ("Y", or "N" ) as part of args, then if Y is selected show message "You have selected Y", if N is selected
      then show "You have sekected N" , if any other char is passed then show message "Invalid entry" 
      
      e.g arg passed : Y
      Output : You have selected Y
      
      e.g arg passed : S
      Output : Invalid entry

TODO : To create a method which accepts Operation and two integers as part of args ,
    Valid operations are "Add", "Subtract" , "Multiply" "Divide", give the output as follows ( plz. use switch )
    "Operation Performed : <Operation Type>
    "Input entries : <Display the entries of integers with space in between them
    "Result : Operation output"

    e.g. Args passed :  Add 9 7
    Operation Performed : Add
    Input entries : 9 7
    Result : 16

    if incorrect args are passed
    e.g 2
    Args passed : Integration 9 7
    Invalid Operation performed

    e.g 3
    Args passed : Add 9.5 3
    Invalid integers passed
     

    
TODO : Factorial program
    accept a integer from args and give the output of its factorial value ( HINT : plz use for loop )
    output will be " Factorial of <Number> : "
    e.g. #1
    args passed : 5

    Factorial of 5 : 120

    e.g #2
    args passed: test
    Invalid entry
 

TODO :
    Create an interface with type as Shape having methods as "calculateArea" and "displayArea"
    Create a class Circle, Rectangle and Square which will implement Shape
    each of the give class will have a constructor which will accept the required params
    e.g Circle class will have constructor with radius as parameter
    Rectangle will have width and breadth
    Square will have side
    in App main method. create objects of the Circle , Square and Rectangle ( with required params ) , calculate the area  and display the area
     

TODO : Create a Employee POJO with ( id, name , city )
    In App main, method to create a dummy List of employees ( Siva, Sandipta, Rohan, Harsh and Vineet )
    To show : To display the names of employees with are of given city ( passed as args) ( use enchanced for loop )
    
    e.g. args passed : Pune
    Output : Rohan, Harsh , Vineet
    
    e.g. args passed : xyz
    Output : No such employees present in xyz location
                              
 TODO : Question of above and use Java 8 streams feature to filter it out
                              
 TODO : To display all the employees based on all locations. ( use Map and for loop )
        
         "Chennai" , [ "Siva" ]
         "Kolkata" , [ "Sandipta" ]
         "Pune", [ "Rohan", "Harsh", "Vineet" ]
                              
 TODO : Question of above and use Java streams feature to display the Map
                              
