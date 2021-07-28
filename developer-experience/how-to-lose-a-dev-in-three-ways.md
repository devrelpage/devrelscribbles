---
description: >-
  Jamie Wittenberg talks about great ways you can incorporate to make your
  documentation better and more accessible to new developers.
---

# How to lose a dev in three ways

{% embed url="https://youtu.be/1gukQNERjLQ" caption="Video" %}

## Summary

### **Create Inclusive documentation**

* It is the right thing to do for developers but also for the business
* The documentation is someone's first experience with your product
* Your documentation is the best marketing material you might have! 

### **3 ways to lose a dev due to documentation**

* New devs aren't familiar with ****_**code conventions**_
* _**Developer environments**_ are hard
* New devs _**lack context**_ 

### **How to fix this?**

* _**Test your docs**_ on different operating systems and have someone with low development experience try it
* Create a _**legend  & glossary**_ for your documentation
* _**Add context**_ to your tutorials

## Scribbles

### **Edge cases for great product documentation:**

* Users should be able to simulate the development environment
* Users should not be entering their personal information, email addresses or use any credit cards for accessing the documentation
* Users should be able to save their work and return to it.
* Assume that users might not have written a single line of code before
* Users should be able to access everything with even tablets or cell phones  

### **Three ways you might lose new developers due to your documentation**

#### **New developers are not familiar with code conventions**

* _Problem:_
  *  `$ sudo apt update` - Newbies might not understand what a simple `$` here might represent
    * Similarly, 
      * Using `>>>` for interactive shell
      * Using `[ ]` around values where you want people to substitute their API credentials
    * You cannot avoid conventions generally because they increase inclusivity generally
* _Solution_
  * Include a legend in your documentation that defines any conventions used. 
* _Problem:_ 
  * New developers aren't familiar with developer workflows, such as when to use the command line vs a text editor.
    * Eg: Newbies might get confused what part of documentation represents shellcode and what represents javascript code.
* _Solution_ 
  * Use visual differentiation to indicate different parts of the developer workflow
    * Use syntax formatting, number lines, etc,
    * Different parts to indicate output vs input files, code vs shell etc. 
* _Problem:_ 
  * Even with the best explanations, some of the things might get lost.
* _Solution_
  * Use screencast or gifs to make developers aware of the process. 

#### **Developer Environments are hard**

* Don't assume the operating system one might be using for accessing your code.
  * Eg.: A lot of documentation assume people using UNIX/ Linux systems and Windows users might get discluded. 
* _Solution 1_
  * Link to someone else's explanation of how to use different operating systems.
  * Write your own detailed solution for these specific cases: More involved and yields greater benefits by keeping developer on your platform
* _Solution 2_
  * Explain command and environmental differences, using a different platform, shells and respective commands for that
* _Solution 3_
  * Set up examples on Codepen, Glitch or repl.it, where they can run and test your documented example code.
* _Solution 4_
  * If a browser-based development environment does not work for your product, use a VPS/ VM solution for that.

#### **New devs lack context**

* _New Developers don't know what your product does_
  * _Solution:_ Add a few sentences at the beginning of the quickstart and tutorials. Include key activities. 
* _Your docs are expansive and hard for a new dev to navigate_
  * _Solution:_ ****Provide use cases for your product and use them to guide developers through your documentation 
* _Your docs are hard to find or your product requires signing up to test_
  * _Solution:_ Create a sandbox 

### **What you can do to fix this tomorrow?**

* Have a friend with less development experience try one of your tutorials and document every confusing point
* Test your docs on different operating systems
* Create a legend for your documentation
* Add a glossary to your documentation
* Add context to your tutorials





