# C

**Call stack** - a list of methods that have been called in the order in which they were called. Typically, the most recently called method (the current method) is thought of as being at the top of the call stack


**Casting** - casting is the conversion of one type to another type.  Typically, casting is used to convert an object reference to either a subtype (for example casting an Animal reference to a Horse), but casting can also be used on primitive types to convert a larger type to a smaller type, such as from a _long_ to an _int_.


**char** - a 16-bit unsigned primitive data type that holds a single.  Unicode character.


**Character literals**  - these are represented by a single character in single quotes such as 'A'.


**Child class** - _See_ Derived class


**Class** - the definition of a type.  It is the blueprint used to construct objects of that type.


**Class members** - things that belong to a class including methods (static and nonstatic), variables (static and nonstatic), and nested classes (static and nonstatic).  Class members can have any of the four access control levels (public, private, protected, default(package)).


**Class methods** - often referred to as a static method, may be accessed directly from a class, without instantiating the class first.


**Collection** - an object used to store other objects.  Collections are also commonly referred to as containers.  Two common examples of collections are HashMap and ArrayList.


**Collection Interface** - defines the public interface that is common to Set and List collection classes.  Map classes (such as HashMap and Hashtable) do not implement Collection, but are still considered part of the collection framework.


**Collection framework** - Three elements (interfaces, implementations, and algorithms) create what is known as the collection framework, and include Sets (Which contain no duplicates), Lists (which can be accessed by an index position), and Maps (which can be accessed by a unique identifier).


**Comparison operators** - perform a comparison on two parameters and return a boolean value indicating if the comparison is _true_.  For example, the comparison 2 < 4 will result in _true_ while the comparison 4 == 7 will result in _false_.


**Constructor** - A method-like block of code that is called when the object is created (instantiated).  Typically, constructors initialise dat numbers and acquire whatever resources the object may require.  It is the code that runs before the object can be referenced.


**continue statement** - causes the current iteration of the innermost loop to cease and the next iteration of the same loop to start if the condition of the loop is met.  In the case of using a _continue_ statement with a _for_ loop, you need to consider the effects that the cntinue has on the loop iterator (the iteration expression will run immediately after the _continue_ statement)
