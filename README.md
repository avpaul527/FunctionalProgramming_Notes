# Functional Programming Notes
# *Functional Programming with Java*
(Focus on: Lambdas, Method Reference, Maps and Filters)

- Bootstrapping - Using one initial, basic program to load and execute a more complex program.

- Imperitive Approach to Programming - Defining every single detail about your application.
  - Ex: using if statements for each condition.
- Declaritive Approach - Telling your application exactly what you want it to do.
  - Ex: Using the .stream() method to declare what is to be done.
- Package java.util.function - Functional interfaces provide target types for lambda expressions and method references.
  - Functional method - Single abstract method for each functional interface matched/adapted to lambda expressions parameter and return types.
  - Ex: Predicate function  - returns true or false based on the type of object
    - Ex[ex]:
    - Imperitive Approach: *(Predicate<Object> objectPredicate = object -> ATTRIBUTEassn.equals(object.attribute);)*
    - Declarative Approach: *List<Object> objectName = objects.stream() [enter] .filter(objectPredicate) [enter} .collect(Collectors.toList()); [enter] objectName.forEach(System.out::println);*
  - 
