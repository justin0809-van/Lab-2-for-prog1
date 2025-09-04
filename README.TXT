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

