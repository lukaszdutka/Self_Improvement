# Chapter 2. A tale of two values

Every software system provides two values to business: behavior and structure.

### Behavior
It's first value of software. Programmers are hired to make machines
behave in a way that makes or saves money.

Many programmers thinks that this (and bugfixing) is enough. It is not.

### Architecture
Software must be "soft" - easy to change.

Difficulty of change should be proportional only to the scope of change and not
the shape of the change.

The more architecture prefers one shape over another, the more likely new features 
will be harder and harder to fit into that structure.

Architecture should be as shape agnostic as practical. 

### Eisenhower's matrix.

The first value of software - Behavior - is urgent, but not always particularly important.  
The second value of software - Architecture - is important, but never particularly urgent. 

1. Urgent and important
2. Not urgent and important
3. Urgent and not important
4. Not urgent and not important

Architecture (the important stuff) is 1 and 2.
Behavior (the urgent stuff) is at 1 and 3. 

Business and developers often elevate items in position 3 to position 1.
They fail to separate urgent not important features from those truly urgent and important.

Business managers are not always capable of evaluating importance of architecture.
Our job as software developers is to do it. We are hired for it. 

### Fight for the architecture
Your duty, as a software developer, is to safeguard architecture 
for the good of the product.

It is doubly important if you are software architect. 

If architecture is last priority, then system will become even more costly to develop,
and eventually change will become impossible (not profitable).

### Starting with the bricks: Programming paradigms

Today, there are three programming paradigms.

### Tips

You, as a software developer, have to think about architecture and push 
development of it.

### Quotes

> Things that are urgent are rarely of great importance, and those things
 that are important are seldom of great urgency.

### Easy Example

Creating calculator. New revolutionary feature: division.
You test, divide by 1 gives the same number. Divide by 10 shifts comma.
You commit it and push, task done. Now you have to work on new even more 
revolutionary feature - squaring numbers.
Then, after 2 weeks of development release comes. 
ERROR divide by 0, not tested. 2 weeks after you need to 
go back to code you wrote and deploy it again. Bad architecture.

Q: Isn't it more infrastructure than architecture? 

### Thoughts

Programming to make money is like fishing from pond without thinking 
about fish population. You can go as fast as you can and maybe get 
more fish, but then it will die and you won't be able to fish anymore.  
PSW is not restocking (zarybia) enough. :P

### Questions    
- Does programmers most important job is to make machines 
behave in a way that makes or saves money?
- What makes software easy to change?
- What is the shape of change?
- What is the scope of change?
- What is the difference between scope and shape of change?
- What is more important: software system to work or is it more 
important for it to be easy to change?
