# hexagonal-architecture-in-java


Advantages of the Hexagonal architecture:

Easy to maintain: Since the core application logic(classes and objects) is isolated from the outside world and it is loosely coupled, it is easier to maintain. It is easier to add some new features in either of the layers without touching the other one.

Easy to adapt new changes: Since all the layers are independent and if we want to add or replace a new database, we just need to replace or add the database adapters, without changing the domain logic of an application.

Easy to test: Testing becomes easy. We can write the test cases for each layer by just mocking the ports using the mock adapters.
