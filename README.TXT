Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.


Question 2: The balance goes back to 0.

Question 3: I notice that even if i insert a value lower than the cost of the ticket, the ticket still prints.
Unfortunately, i did not receive any refunds even if i inserted too much money, higher than the ticket price.
The ticket will still be printed even if you the value you inserted is lower than the ticket price.

Question 5: Nope, doesn't look any different. Besides from the fact i changed ticket price, nothing changed.

Question 6:

Question 7: It does matter. Otherwise, we will receive an error related to the classes if we try to compile.
I noticed a change. THe diagram is filled with crossed red stripes, indicating an error in the code.

The error message i received when i try to compile the file are:

- class, interface, enum or record expected.
- <identifier> expected.
- unnamed classes are a preview by default... etc

Question 8: It is possible to leave out the word public. I successfully compiled it, inserted money, printed a ticket and everything.
Everything works perfectly fine.

Question 9: It is not possible to leave out the word class. I receive the same error codes from question 7. To conclude, classes plays a bigger role than public. 

Question 10: The lists.
fields:
    private int price;
    private int balance;
    private int total;
constructors:public TicketMachine(int cost)
methods:public int getPrice()
public int getBalance()
public void insertMoney(int amount)
public void printTicket()

Question 11: The difference between the constructors and methods are:
1) There no "ints" nor "voids" placed before the word "public" which makes it different. 
2) The class name of the instructor matches with the inital class name which is different from the methods since they are methods.

Question 12:
1) the type of field "int" belongs to is instance variable.
2) the type of field "Student" belongs to is class variable.
3) the type of field "Server" belongs to is Class variable.

Question 13:the names for each of these fields are
1) boolean
2) Person
3) Game

Question 14)all the type of names that starts with a capital are Classes.

Question 15)Yes, the order of the command private int class; matters otherwise it wouldnt work. 
One of the error codes that appeared when i switched it to "private class int;" was "<identifier expected>". As for the diagram,
its crossed red lines.
Another error that shows after i typed "int private class;" was <identifier expected>. As for the diagram, same thing. Red lines.
I've come to the conclusion that in any other orders the command is built in, the error code and the diagram are the same.

Question 16) Its very necessary to have a semi-colon at the end of a field because it indicates the end of a command of the 
field. It also prevents errors from happening. After I experimented with the editor, removing the semi-colons doesn't allow me to 
compile anything. Error code is "";" is expected". I understand that semi-colons plays a crucial role when coding.

Question 17)private status int;

Question 18)The class that this constructor public Student(String name) belongs to is the Student class.
    
Question 19)This following constructor have 2 parameters.

Question 20)Yes, i think it should be stored somewhere persistent for it to not lose data.
No we cant guess the type of fields it has from the parameters because they two different things and no we cant know anything for sure
since they are different.

Question 21) 
public Pet(String petsName)
{             
   Pet = petsName
}   

Question 22)

public Date(String Month, int Date, int Year)
     Month = "March";
     Date = 23
     Year = 1861
    
Question 23)The difference is that they have different method names. Balance and Price.

Question 24) it can be set as "Whats my balance?"

Question 25) Nope, the return statement does not need modifications since the code works perfectly fine, no error codes.
This tells me that the accessor method can be different than the name of the field.

Question 26) I added and it worked perfectly fine.
/**
 * Return the value of the total field
 * 
 */
public int getTotal()
 {
     return total;
 }
                     
 
Question 27) The error message i recieve is "not a statement"

Question 28) The main difference is located in the header part. The header for getPrice has int and for printTicket, it has void.

Question 29) insertMoney and printTicket doesnt have any return statement because they both have Void, which means it cant return any value.

Question 30)
getBalance = 0
inserted 40
new balance is now 40

Question 31)
/**
* Increase score by the given number of points.
*/
public void increaseScore(int points)
{
    score = score + points;
}    
    
Question 32) Yes, it acts as a mutator because it changes the score of the Class


Question 33)
/**
* Reduce price by the given amount.
*/
public void decreasePrice(int discount)
{
   price = price - discount;
}


Question 34)

public int setAge(int currentAge)
{
    Age = currentAge
}

Question 35)

private void setAlive(boolean status)
{
    alive = status;
}    

Question 36)After changing the parameter to price and matching (price = price), the value of the 
price is 0 after i inserted the cost. Always 0. But if i change it back to cost, in the editor, the
value registers.

Question 37)The command will print exactly these following: "My cat has green eyes"

Question 38) Here is the command i inserted. It has no syntax errors.
    /**
     * Please insert the right amount of money.
     */
    public void prompt()
    {
        System.out.println("Please insert the right amount of money");
    }

Question 39) the following command should print out "#pricecents."

Question 40) the following command should print out "# price cents."

Question 41) The command i used is 
Public void showPrice()
    {
        System.out.println("The price of the ticket is " + price + "cents.");
    }
    
Question 42)The outputs are the same but its 0. I believe there wasnt a code written beforehand that allows
it to work.

Question 43)It does print the same output, but its 0. I dont understand what the command means
but its surely not working for me.

Question 44)
        
        