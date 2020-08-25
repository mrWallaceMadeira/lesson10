# Reduce, reuse, recycle
We introduced if/else statements which allowed some code to be executed and some to be 'ignored'\
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
  for (int i = 0; i < 5; i++) {
    System.out.println("hello");
  }
```
:eyes: &nbsp; Notice
  - [x] We declare a variable `i` and assign it the value 0
  - [x] We see a conditional statement `i < 5`

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
 
 The structure of for and while loops is essentially the same.\
 They differ in their organization.\
 
 ### Let's abstract a bit
 ###### For loops take this form 
 ```
  for (declare and initialize counter; set counter condition; set counter increment) {
    do stuff;
  }
 ```
 ###### While loops take this form
 ```
  declare & initialize counter;
  while (set counter condition) {
    do stuff;
    set counter increment;
  }
 ```
 We have the same pieces, just rearranged.
 Our pieces are
  1. declare and initialize counter à la `int i = 0;`
  2. set counter condition à la `i < 5`
  3. set counter increment à la `i++`
      - This is the same as `i = i + 1;` or `i += 1;`
 
 ### :tv:&nbsp;Fernsehzeit!
 Watch [this](https://themadeiraschool.sharepoint.com/sites/IntrotoCS/Shared%20Documents/General/Videos/lesson10Video1.mov)
 
 ### :performing_arts:&nbsp; C'est fini
 Entry ticket [here](https://forms.office.com/Pages/ResponsePage.aspx?id=P9fbuiFvgkyZJ5ogeV5C0bXAAGShYuhAq0O_bKHZJnxUNzRLSE5QWjBVMzRYREJCMkFLTTE0TzZKTyQlQCN0PWcu)
 

