---
description: >-
  Cristiano Betta shares the practicalities of how they have taken an
  engineering approach to their API documentation.
---

# Docs as engineering: an intro to developer experience engineering

{% embed url="https://youtu.be/UT3qOCmgLV8" caption="Video" %}

## **Summary:**

#### Docs as Code

* **Store your documentation in GitHub or SVN**, or whatever you want to use, but these days a lot of it is in Git. 
* **Build** the documentation automatically. 
* **Review** the documentation as you write it. 
* **Publish** the documentation without much user intervention. 
* **Test** anything that can be tested. 
  * Making sure that your documentation quality is gonna remain good going forward.
  * That kind of thing. 
* **Modularize** to prevent duplication, 
  * So that we can reuse our documentation.
* **Reuse** --  All of that will allow us to maximize value. 
* Using a **pipeline** to tie it all together.



## **Scribbles:**

* README allows you to make a backup, you export it.
* Turns out when you do import and export and import kind of thing, you’d expect it to be symmetrical. If I create export and I just import it over here again and should be getting the same system at the end. Not how it worked at ReadMe.

### Problems 

#### What were the problems faced during the process of translation?

* Hard to translate 
* No audit trail l
* No review process 
* No modularity 
* Hard to refactor 
* Hard to ensure quality 

### Docs as Code concept

* **Store your documentation in GitHub or SVN**, or whatever you want to use, but these days a lot of it is in Git. 
* **Build the documentation automatically.** 
* **Review the documentation as you write it.** 
* **Publish the documentation without much user intervention.** ‌

### Docs as Engineering 

* Necessarily not covering architecture -- but software engineering.
* Software engineering, we’ve got a lot of principles that we’re all familiar with.

We have the idea that we should be 

* Modularity: Writing modular code, and that we should 
* KISS: Keep things simple, and that we 
* DRY: Shouldn’t repeat ourselves, and that we should 
* **Anticipate change** 
* Do one thing well: The Unix principle of doing things well. 
* To test early 

### Testing and linting 

* Testing early, 
* Testing often, 
* Testing the parts 
* Testing the whole. 
  * Validate internal links
* Test at the source. 
  * For documentation, that means that if you test early, you want to There’s a couple of things you can do there. 
* Test the unit. 
  * Spell-checking. 

### Modularising

It’s the idea that you should break things into their components to make sure that they do one thing well, that they allow for easy inclusion.

* Do one thing well
* Allow for easy inclusion 
* Composition over configurations
* And you allow composition over configuration.
* So rather than configuring things, you can take multiple components that you’ve written, combine them together into some nice, new bits of software
* Apply that same thing to our documentation.

### Pipeline

* Ensure quality. 
  * So within the pipeline, we do our testing, we do our validation that our code still does what it’s supposed to do. 
* It maximizes our value 
  * It allows us to ship to multiple locations quickly, faster, in parallel. 
* It speeds up delivery 
* Encourages responsibility. 
  * Because it basically says, hey anybody who documents, anybody who writes software, if you manage to merge this into master, it will ship, it will go live, it will be part of the product, it will go out there almost instantly.

‌

#### Box’s Docs Pipeline

Let’s look at the pipeline Cristiano’s team created to automate literally everything! 

![](https://lh6.googleusercontent.com/LFFuxKOZCGb9nxUlP3a-eDZvoDH1MXBRiCp2smeXmK0S-_qhnVaGZ15joyJEeEoyO-IbjNUm1ZfONotSaJpIMIoDDgIL1Y15qI9-3iBJjBXchAru0dIr7BzCwDOBJDt96wmbTjs)

* _**Microcopy and guides**_
  * This stuff is mostly markdown and a couple of YML files, as well as their open API specification, which is mostly YML. 
* _**Travis**_ 
  * Pick it up, do the spellchecks, do all the validation, etc. And then it writes it back to an English branch\(English version\).
  * Every time the on branches get updated, or any time their SDK’s or Gatsby kind of source, which is the static site generator that they use.
* _**Netlify**_ 
  * The serverless function basically determines which of our stages to trigger. 
  * Staging environment, master environment, and translation environment for their upcoming Japanese full translation. 
  * Netlify will pull all those sources in, build the site.  
  * Netlify -- also as a hosting provider.
* They took it a step further and they were not just building documentation at that point because.

> We have great source materials now that we are validating and we’re sanitizing.

![](https://lh3.googleusercontent.com/Yvc2Ra6-Bh9aYvCf-Jzbs92Xb_oVE_P_aTGzm8nqoXhrweaQFUsctRQy-0YTzpOg0k0g8oRqaaK7jWhDLc3kDOwuvpoDYHF7ueAoRcAAC-3n6sIPyGMlyeCO9a4yrU2p3zrbFaY)

* **Different build servers** -- at the bottom, we have our in-house build server. So every time our English sources change, it creates a snapshot, translates it in house, sends it off to our translation teams, and then writes back to the Japanese file to a Japanese branch. 
* Netlify will pick up any of these sources and build them out as documentation. But every time these sources change, Travis will also put it up and currently it’s pushing a postman collection.
* And it’s not just pushing it out in English, it’s also pushing it out in Japanese!!

