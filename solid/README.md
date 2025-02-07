# Python S.O.L.I.D Principles - Create more classes

### Why follow SOLID?
- Use SOLID principles to address design deficiencies
- Some problems without SOLID
  - Mixed responsibility 
  - Missing responsibility
  - Limited reuse potential
  - Not substitutable

### S.O.L.I.D - Order doesn't matter
1. Interface segregation
    1. Helps design good classes
    2. Helps write unit test cases
    3. Asks you to create a different interface for different responsibilities, in other words, don't group unrelated behavior in one interface, You break ISP if You have already an interface with many responsibilities, and the implementor doesn't need all this stuff.
    4. [https://stackoverflow.com/questions/54480725/the-difference-between-liskov-substitution-principle-and-interface-segregation-p](https://stackoverflow.com/questions/54480725/the-difference-between-liskov-substitution-principle-and-interface-segregation-p) 
2. Liskov substitution - how subclasses extend superclasses
    1. This principle asks you to make sure that all child classes have the same behavior as the parent class. Object of superclass S can be replaced with objects of any subclass of S. 
    2. Helps design good polymorphism
    3. Ex: Square-Rectangle Problem
3. Open/closed - tuning the design
    1. Open to extension means adding subclasses a needed
    2. Closed to modification avoids "tweaking" the code to handle new situations
    3. A**llow its behavior to be extended without modifying its source code. Factory → we need to update the objects list only, method names are the same.** 
4. Dependency inversion - based on packaging the code. Decrease the dependency on another concrete class.
    1. A direct dependency on a concrete class needs to be "inverted"
    2. Depend on abstraction classes
    3. Avoid concrete class name dependencies
5. Single responsibility - summary of other 4 principles
    1. One responsibility per class. 
    2. "A class should have one reason to change"
    3. Note!! "Single" at what level of abstraction? How are the responsibilities counter?

### Other OO Principle
- Don't repeat yourself (DRY)
- General responsibility assignment software principles (GRASP)
- Test-driven development (TDD)

## Resources
- https://github.com/heykarimoff/solid.python/
- https://www.linkedin.com/learning/learning-s-o-l-i-d-programming-principles
- https://www.pythontutorial.net/python-oop/python-single-responsibility-principle/
