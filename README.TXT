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

question 2: there is a balance of 0 after printing a ticket
question 3: integrer number too large, no refunds, even if the balance isn't enough it prints a ticket anyway
question 5: the "cents" value is different (meaning that the price value is different)
question 7: yes it does. the correct order would be "visibility modifier", "type" and "variable name". the correct way to write it would then be "public class TicketMachine". when instead compiling "class public TicketMachine", BlueJ detects an error.
question 8: it is indeed possible to leave out the word "public" from the outer wrapper of the TicketMachine class without having any errors
question 9: an error is detected when removing "class"
question 12: int /Student/ Server
question 13: alive/ tutor/ game
question 14: 
question 15: changing the order of "private int price" in any way will cause an error
question 16: it IS necessary to always put a semicolon at the end of a field declaration, otherwise an error will appear
question 17: "private int status;"
question 18: it belongs to the Student class
question 19: two parameters
question 20: yes. by checking the source code.
question 21: pet=name;
question 23: the method name 
question 24: "How much money does the customer have?"
question 25: if the name getBalance is changed to getAmount, the return statement doesn't need to be modified for the code to be properly compiled. the accessor field relies on the name of the field associated with it, which would be "private int balance;"
question 27: error found in class
question 28: different types (int and void respectively) , the body of printTicket is much longer
question 29: no, they do not have return statements, since they are void methods
question 31: /**
 * Increase score by the given number of points.
 */
public void increaseScore(int points)
{
    score += points;
}
question 32: yes, it is a mutator object because it modifies the "credits field" by adding "additionalPoints"
question 33: 
    public void discount(int amount)
{
    if (amount > 0 && amount <= price) {
        price -= amount;
    } else {
        System.out.println("Invalid discount amount.");
    }
quesation 34: 

