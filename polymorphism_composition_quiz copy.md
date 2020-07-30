# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
Poly = many
morph = change
Can have many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

the ability to process objects differently based on their class

public interface IChargeable {
    double getTransactionCost(double purchaseAmount);
    void charge(double purchaseAmount);
}

3. What can we use to implement polymorphism in Java?
interfaces

4. How many 'forms' can an object take when using polymorphism?
unlimited
5. Give an example of when you could use polymorphism.
When you are using an abstract class 


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
when we have objects inside of the objects and objects which rely on one another

7. When would you use composition? Provide a simple example in Java.

When we want to have parents that don't rely on children
public class Customer {
    private Double wallet;
    private ArrayList<Vehicle> garage;

8. What is/are the advantage(s) of using composition?

Allows technically for multiple inheritence

9. When an object is destroyed, what happens to all the objects it is composed of?
They also will be removed