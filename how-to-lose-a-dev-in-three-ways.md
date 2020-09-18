---
description: >-
  Jamie talks about great ways you can incorporate to make your documentation
  much better and accessible to new developers.
---

# How to lose a dev in three ways

{% embed url="https://www.youtube.com/watch?v=1gukQNERjLQ&ab\_channel=DevRel" caption="Jamie Wittenberg \(MLH\) - DevRelCon San Francisco 2019" %}

### Summary

* Create **Inclusive documentation**
  * It is the right thing to do for developers but also for the business
  * The documentation is someone's first experience with your product
  * Your documentation is the best marketing material you might have!
* **3 ways of to lose a dev due to documentation**
  * New devs aren't familiar with **code conventions**
  * **Developer environments** are hard
  * New devs **lack context**
* **How to fix this?**
  * **Test your docs** on different operating systems and have someone with low development experience try it
  * Create a **legend  & glossary** for your documentation
  * **Add context** to your tutorials

### Scribbles

* _**Edge cases for great product documentation:**_
  * Users should be able to simulate the development environment
  * Users should not be entering their personal information, email addresses or use any credit cards for accessing the documentation
  * Users should be able to save their work and return to it.
  * Assume that users might not have written a single line of code before
  * Users should be able to access everything with even tablets or cell phones 
* _**Three ways you might lose new developers due to your documentation**_
  * **New developers are not familiar with code conventions**
    * **Problem:** `$ sudo apt update` - Newbies might not understand what a simple `$` here might represent
      * Similarly, 
        * Using `>>>` for interactive shell
        * Using `[ ]` around values where you want people to substitute their API credentials
      * You cannot avoid conventions generally because they increase inclusivity generally
    * **Solution**
      * Include a legend in your documentation that defines any conventions used.
    * **Problem:** New developers **aren't familiar with developer workflows**, such as when to use the command line vs a text editor.
      * Eg: Newbies might get confused what part of documentation represents shellcode and what represents javascript code.
    * **Solution** 
      * Use visual differentiation to indicate different parts of the developer workflow
        * Use syntax formatting, number lines, etc,
        * Different parts to indicate output vs input files, code vs shell etc.
    * **Problem: Even with the best explanations, some of the things might get lost.**
    * **Solution**
      * Use screencast or gifs to make developers aware of the process. 
  * **Developer Environments are hard**
    * Don't assume the operating system one might be using for accessing your code.
      * Eg.: A lot of documentation assume people using UNIX/ Linux systems and Windows users might get discluded. 
    * **Solution 1**
      * Link to someone else's explanation of how to use different operating systems.
      * Write your own detailed solution for these specific cases: More involved and yields greater benefits by keeping developer on your platform
    * **Solution 2**
      * Explain command and environmental differences, using a different platform, shells and respective commands for that
    * **Solution 3**
      * Set up examples on Codepen, Glitch or repl.it, where they can run and test your documented example code.
    * **Solution 4**
      * If a browser-based development environment does not work for your product, use a VPS/ VM solution for that.
  * **New devs lack context**
    * **New Developers don't know what your product does**
      * **Solution:** Add a few sentences at the beginning of the quickstart and tutorials. Include key activities.
    * **Your docs are expansive and hard for a new dev to navigate**
      * **Solution:** Provide use cases for your product and use them to guide developers through your documentation
    * **Your docs are hard to find or your product requires sign up to test**
      * **Solution:** Create a sandbox
* _**What you can do to fix this tomorrow?**_

  * Have a friend with less development experience try one of your tutorials and document every confusing point
  * Test your docs on different operating systems
  * Create a legend for your documentation
  * Add a glossary to your documentation
  * Add context to your tutorials

