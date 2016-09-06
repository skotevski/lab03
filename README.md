# lab03

## What do you think is the type of each of the following fields? 
* private int count; The type of this field would be integer. 
* private Student representative; The type of this field would be a class, known as Student.  
* private Server host; The type of this field would be a class, known as Server.

## What are the names of the following fields? 
* private boolean alive; The name of this field would be alive. 
* private Person tutor; The name of this field would be tutor.  
* private Game game; The name of this field would be game. 

## From what you know about the naming conventions for classes, which of the type names in teh above questions would you say are class names? 
The type names in the above questions that I believe are class names are Student, Server, Person, and Game.
## In the following field declaration from the `TicketMachine` class  
```
private int price;
```
does it matter which order the three words appear in? Edit the TicketMachine class to try different orderings. After each change, close the editor. Does the appearance of the class diagram after each change give you a clue as to whether or not other orderings are possible? Check by pressing the Compile button to see if there is an error message. Make sure that you reinstate the original version after your experiments! 

Yes, the order that the three words appear in matters. If you were to write private in the middle of int and price, then the code would not be able to function properly, because it does not know what type is exactly becoming private, although if you were to remove private entirely, then it would still work as it was originally intended. 


## Is it always necessary to have a semicolon at the end of a field declaration? Once again, experiment via the editor. The rule you will learn here is an important one, so be sure to remember it. 
Yes, it is always necessary to have a semiclon at the end of a field declaration, because if you do not include a semicolon, the field declaration does not come to a finish, and that will end up leading to some kind of compiling error.

## Write in full the declaration for a field of type `int` whose name is `status`.

## To what class does the following constructor belong?
```
public Student(String name)
```
That constructor belongs to class Student.

## How many parameters does the following constructor have, and what are their types?
```
public Book(String title, double price)
```
That constructor has 2 parameters, and the types of the parameters are string and double. 

## Can you guess what types some of the `Book` class’s fields might be, from the parameters in its constructor? Can you assume anything about the names of its fields?
The types that some of the 'Book' class's fields might be are String and double based on the parameters in its constructor. I can also assume that the names of its fields would have to be similar to the parameters. 


## Suppose that the class `Pet` has a field called `name` that is of the type `String`. Write an assignment statement in the body of the following constructor so that the `name` field will be initialized with the value of the constructor’s parameter.
```
public Pet(String petsName)
{
  name = petsName;
}
```
## The following object creation will result in the constructor of the `Date` class being called. Can you write the constructor’s header?
```
public Date (String month, int date, int year)
new Date("March", 23, 1861)
```

Try to give meaningful names to the parameters.
