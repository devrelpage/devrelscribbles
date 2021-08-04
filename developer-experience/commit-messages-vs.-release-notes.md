---
description: >-
  Can you make good release notes by collating your commit messages? Eva Parish
  argues not. Eva Parish explains the different purposes of commit messages and
  release notes.
---

# Commit messages vs. release notes

{% embed url="https://youtu.be/9L8rgOjiGAM" caption="Video" %}

## Summary:

* _**Why don’t we just scrape a list of all the commits that went into the last release, and boom, instant release notes?”**_ 
* Having well written and consistent commit messages are important and having great release notes is also important, the two are not interchangeable. 
* **Commit messages** are terse technical descriptions of what you’ve changed in a unit of work and why, for an audience of developers.
  * Commit messages are a chance to capture the context around what you’ve done in a way that will make things easier for your future self and your coworkers.
  * It only takes a few extra seconds of brainpower to write a commit message that’s useful  
* **Release notes** are a list of the important user-facing changes in a release, generally written at a less technical level of detail and focusing more on behaviour.
  * Release notes are an excellent opportunity to tell your users about the awesome thing you’ve built and why they should use it.

## Scribbles:

### Commit messages 

* _**Commit messages to record brief technical details of what you’ve changed in a unit of work.**_  
* Be brief but still complete enough that someone can get a sense of what happened.
* Why are you making this change? 
* It’s less important to focus on the details of how you accomplish something‌.

#### Audience

* You can assume that your reader is pretty technical but they don’t have all the context.
* This is why it’s important to include the reasoning. 

> _**On my team, we like to say that good documentation is like a love letter to your future self**_.

### Release notes

* _**A high-level and less technical summary of what’s changed about a product or a feature or an API in a release.**_ 
* Your release notes should be written at a less technical level than your commit messages. 
* Focus on the resulting behaviour and not how you did it. 
* Release notes should be framed from the perspective of the end-user. 

### ‌Audience

* Your users and there’s a wide range, depending on what your product is. 
* Your users might be super non-technical or they might be developers just like you. 
* Think about what information they need to know. 
  * Did you make some kind of improvement? 
  * Did you change how something existing works? 
  * Will they need to refactor code to remove an API you deprecated? 
  * What will look or feel different to them when they’re using the product?

‌

### Comparison

#### Commit Messages

![Example of a new version of the emoji library to make emojis out of gifs.](https://lh5.googleusercontent.com/LdGZvCwY5A7n86Fy03FqzaWfOH1up0nTPizGvX_prMnw2dYWBtEL7ifcKItYfk0hMPDx1VFRsNmwJnvpzqjpsxPbrvqbKUiJQhzU2fOzElrd4msLFxRoU55zL388yMDDsM1xZXY)

* There’s a ticket number, it starts with a verb in the imperative.
* It briefly mentions all the pertinent details, 
  * The library name 
  * The version number 
  * Efficiently states “why”, which is -- support for gifs.

#### 

#### Release note 

![](https://lh5.googleusercontent.com/8OM6p7T26xXBJvVF_DAOVGvcoi3hDnpCu_zVKXvhl5YHaH7fyPpVgv6TcrC_2LHR0t-_aHiJW0_cvTsQPxUyjnyFe7N_9AZtIasrwlGmoseUSzDcd5hDVVIT2SAiyX3fFsr8bew)

* You have a bit more room for information in a release note. 
* Starts by talking about what the change enables the user to do. 
* Links out to further reading, where they can get help if needed.
* And it ends with inspiration for what the user can do to get started using this new thing. ‌

#### How do you get started writing great release notes? 

* Don't **recycle wholesale.**
* You can _**look back through your Git history**_ to remind yourself of what you’ve done, 
  * Pick out the **changes that are most interesting** or impactful to a user. 
* And feel free to leave things out because there are plenty of things in your Git history that a user doesn’t care about. 
* Take each one and imagine it from your user’s perspective. 
  * How will this affect them?
  * What differences will they notice in the product? 
  * Are there any breaking changes or actions that they have to take? 
* Adjust the level of technical detail as appropriate, based on what you know about your users.



> _**“Good release notes get users excited about the hard work that you’ve put in to building your product. So use both commit messages and release notes appropriately and don’t waste these opportunities.”**_

