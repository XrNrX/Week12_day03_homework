# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

A) many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

A) The assigning of different classes or types to a common type/class to then be stored in the
  same ArrayList. An example of this would be if we had classes "SpeedBoat" and "CruiseLiner" which share commonality but cannot be included in the same ArrayList, using Polymorphism we can "extend" them to a superclass called "seaVessel" or "implement" then to an interface called "ISail" to then allow ArrayList functionality over the different Types/classes.

3. What can we use to implement polymorphism in Java?

A) "extends" by using inheritance (abstract class) or "implements" using an interface.

4. How many 'forms' can an object take when using polymorphism?

A) By definition it can take 'many'. (as much as u want i'd guess!)

5. Give an example of when you could use polymorphism.

A) If we had type "Ball" and "Wheel", they could both have the interface "IRoll" which allows them to then have a common ArrayList and therefore extra functionality within our program.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

A) Breaking our program into smaller parts.

7. When would you use composition? Provide a simple example in Java.

A) A) An object could be created that has multiple components, ie A Car would have the compoents Engine and Tyres.

8. What is/are the advantage(s) of using composition?

A) Easy Scalability in the programs future life cycle.

9. When an object is destroyed, what happens to all the objects it is composed of?

A) ALl the lower components are destroyed aswell.
