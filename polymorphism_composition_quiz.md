# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean? Many shapes or forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example. It describes the concept that objects of different types can be accessed through the same interface. For example: Car class can inherit from vehicle and can be treated as a vehicle. So, car can use a function from vehicle.

3. What can we use to implement polymorphism in Java? Inheritance and Interfaces.

4. How many 'forms' can an object take when using polymorphism? We can use as many as we want.

5. Give an example of when you could use polymorphism. Vehicle super Class and car subclasses. Subclasses inherit methodes from super class.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming? It describes a class that references one or more objects of other classes in instance variables. 

7. When would you use composition? Provide a simple example in Java. Car has an engine and wheels. We dont want to use them independently.

8. Give a difference between composition and aggregation? Aggregation: Child object can be used independently. The whole and the part can exist independently of each other. Composition:Composition is a specialized form of aggregation. In composition, if the parent object is destroyed, then the child objects also cease to exist.

9. What is/are the advantage(s) of using composition/aggregation? A Class can use functions from another class.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of? Child objects are also destroyed, they cannot exist independently.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of? Child objects can exist independently. 