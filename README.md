# Lesson 10: Staying [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
In lesson 9 we introduced if/else statements which allowed some code to be executed and some to be 'ignored'\
Now we'll learn how to not repeat ourselves...or always repeat ourselves?

###### First, an example
```
  System.out.println("hello");
  System.out.println("hello");
  System.out.println("hello");
  System.out.println("hello");
  System.out.println("hello");
  
```
If for some reason, I wanted to print hello 5 times, this is my only option right now.\
I'd say that's pretty repetitive.

### Enter the loop
Just  like if/else, loops allow us to execute code outside the normal flow of the program.\
There are two basic flavors of loops: `for` and `while`

###### For loop example
```
  for (int i = 0; i < 5; i++;) {
    System.out.println("hello");
  }
```
:eyes: &nbsp; Notice
  - [x] We declare a variable `i` and assign it the value 0
  - [x] We see a conditional statement `i < 5`
  - [x] `i++`...?
###### While loop example
```
  int i = 0;
  while (i < 5) {
    System.out.println("hello");
    i++;
  }
```
:eyes: &nbsp; Notice
  - [x] We declare a variable `i` and assign it the value 0
  - [x] We see a conditional statement `i < 5`
  - [x] `i++`...?

