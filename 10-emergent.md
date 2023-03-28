## Clean Classes

Like functions, you should keep your classes small and shouldn't put too much responsibility on a single class. A class shouldn't have to call more than five methods at most.

A nice and clean class starts from the name. The name of the class shouldn't to bee too long or too short, The name of the class should be enough to explain what the class does.

## Single responsibility

The Single Responsibility Principle states that a class or module should have one, and only one, reason to change. SRP is one of the important concepts of object-oriented design and is also simple to understand.

Organize your classes and code in such a way that changes don't cost much technical debt to your team. We want to structure our systems so that we muck with as little as possible when we update them with new or changed features. In an ideal system, we incorporate new features by extending the system, not by making modifications to existing code.

## Emergent Design

**Kent Beck,** The author of *Simple Design* quotes that there are only four rules that a system has to follow in-order to be *simple* and by following these rules your code could be well-structured and clean as well as you would gain more insights into your code.

These four rules are as follows:

1. Your code must run through all the tests.
2. It contains no duplication and is DRY.
3. The developer was able to express his intent.
4. It uses only the required number of classes and methods.

The first rule highlights the importance of testing in software development. If your code is perfect on paper and runs well in production but still you don't have any type of proof that your code will keep running smoothly without any problems. Testing is the proof that verifies the claims of the developer that his code runs without any problems.

Once we have tests, we are empowered to keep our code and classes clean. We do this by incrementally refactoring the code.  During this refactoring step, we can apply anything from the entire body of knowledge about good software design. We can increase cohesion, decrease coupling, separate concerns, modularize system concerns, shrink our functions and classes, choose better names.

Duplication is the primary enemy of a well-designed system. It represents additional work, additional risk, and additional unnecessary complexity. Duplication manifests itself in many forms.

The majority of the cost of a software project is in long-term maintenance. In order to minimize the potential for defects as we introduce change.  As the systems become more complex, they take more and more time for a developer to understand, and there is an ever greater opportunity for a misunderstanding.

Our goal is to keep our overall system small while we are also keeping our functions and classes small.

#web-development #Books 