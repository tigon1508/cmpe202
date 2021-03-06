1.	Without Lambda: we need to create 6 classes to resolve the problem.
2.	But when using Lambda: I only need to use 3 classes (2 of them are original versions from original design pattern source code) to get the same result. 
Moreover, the implementation of Lambda is very easy to understand and very convenience to use because of its simplicity.
We can see that by using lambda expressions will make the additional classes (Decorator, ConcreteDecoratorA, ConcreteDecoratorB) for decorators to be redundant. 
We don�t need these additional classes, keep only Component interface and ConcreteComponent; then simply specify additional behavior using lambda expression into main class (LambdaTest). 
However, there is support for finding the decorator again for re-use. If you have a concrete decorator class, you can reuse it next time as well.

![](images/lambda.png)

Moreover: Using Lambda maybe only suitable for some simple features with simple functions that not contain complicated computation and not have many parameters.
I have applied Lambda to the example of Adapter Pattern as well.
