## Wrapping third party APIs

wrapping third-party APIs is a best practice. When you wrap a third-party API, you minimize your dependencies upon it: You can choose to move to a different library in the future without much penalty. Wrapping also makes it easier to mock out third-party calls when you are testing your own code.

One final advantage of wrapping is that you aren’t tied to a particular vendor’s API design choices. You can define an API that you feel comfortable with.

## Never pass or return Null

Returning Null values instead of a proper return statement in function calls can be a real headache and the program will just go in a frenzy state if their isn't any null checks in the code.

If there is something that is even worse than returning null on function calls then it will have it to be passing Null as function or method arguments.  Unless you are working with an API which expects you to pass null, you should avoid passing null in your code whenever possible.

## Third party code

We all use some type of third-party libraries or frameworks in our code to make our job easier but the developers who make those third-party APIs strive to deliver a product for wide adaptability and that their product can work in almost all types of environments.

While the users of these services want the APIs to be tailored to their specific use-case and these thought processes of both parties can cause a whole lot of problems rather than solving them.

A third-party framework may have a lot of built-in methods and functions that are quite useful but if you only need a few of these functions you would argue that importing the whole framework would just add bloat to your application but coding those functions from scratch would take too much time.

#web-development #Books 