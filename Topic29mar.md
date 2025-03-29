Concepts Used in the Code:

1. Inheritance: The Hod class extends Faculty, inheriting its properties and methods.


2. Method Overriding:

Hod overrides the getDetails() and getDetails(float percent) methods from Faculty.

Hod also overrides the bonus(float percent) method but calls the superclass method using super.bonus(percent).



3. Method Overloading (Polymorphism): getDetails() is overloaded in Faculty and Hod with different parameters.


4. Encapsulation: The Faculty class has private attributes (name, salary) accessed via methods.


5. Dynamic Method Dispatch (Runtime Polymorphism): obj2 is declared as Faculty but instantiated as Hod, so overridden methods from Hod are invoked at runtime.

---
Question 
Q01[https://github.com/Hrithik-James/Java-Practice/blob/main/Questions/Q01.md]
