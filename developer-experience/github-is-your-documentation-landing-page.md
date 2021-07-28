---
description: >-
  Lorna Mitchell covers what it takes to create a README that engages and
  informs developers.
---

# GitHub is your documentation landing page

{% embed url="https://youtu.be/QLC7v1ocODI" caption="Video" %}

## Summary:

* If you are a technical writer by profession then you’ve spent a lot of time perfecting your landing page. You have designed an information architecture. 
  * You have worked extremely hard on understanding the user journey and 
  * The users need it when they arrive on that page.
* _**Your landing page is the home page. It’s the front door of your documentation. ‌**_
* Setting repo standards. 
* How to begin a readme? 
  * Fill out the information -- title, short description, etc. 
  * Understanding the purpose of the repo.
  * Provide links. 
* _**Type of Repositories**_
  * Library code 
  * Tool or demo app 
  * Supporting code.
  *  Doc-as-code 

## Scribbles:

### Begin a README

* Giving your project a _**title and a short explanation**_ of what this is is surprisingly rare on the internet. 
* What’s the purpose of the repo? What’s the scope? Is it supported? Is this something we actively want people to work on? Did we make this once just to show how to do a particular thing? What’s it here for? 
* “Click here to see what we do, click here to signup”
  * gives us a sense of what’s happening where that data is present, so we find that useful. And you may want to do something similar to try and understand the journeys that your users are taking when they’re on a place like GitHub, that you don’t control and maybe can’t get a lot of stats back from. 

> _**"And it’s really important to try to spell things out, especially where you have similar repos. If there is the documentation for this project, link to it.**_"



### Repo Types

W‌hat are the various types of repos already available and do their standards differ from one another? 

* **Library code** 
  * This is an installable thing for you to include in your own applications, that will be helpful. 
  * It is intended to be stable enough for you to use it in production, so it needs really good documentation, really good test coverage, generally absolutely first class everything you can imagine, that’s what we have.
* **Tool or demo app** 
  * Something that’s standalone, you can spin it up, play with it, maybe use it as a basis for something else that you could move on and adapt it to do.
* **Supporting code**
  * Not the whole code but the little snippets of code
  * Helps in understanding the context of its application as seeing the full, working copy and how that plugs together can be incredibly helpful.
*  **Doc-as-code** 
  * When the whole developer portal is an open-source project, it’s on GitHub. It has a readme. 

‌

### Library code README

* _**Prerequisites**_ 
  * What version do you need? What programming language is this for? What version do you need to be running? Are there any extra complicated installations? 
  * Like any system libraries, or anything that you need? Are there any operating systems that are not supported? Spell it out. 
*  _**Installation instructions**_
  * Really experienced developers don’t need really detailed instructions. But really experienced developers are really experienced skip-readers.
  * More is great too. 
    * So just write down what you need to type, make it easy. And that includes everybody, it’s appropriate for everybody.
* _**Usage instructions**_ You’ve installed it. You’ve told me how to run the server, now tell me what port it’s on. Tell me what path to append to the URL.
  * Give folks a clue. “How do I, yes I have installed it, how do I do the thing? I want to do the thing, I’m ready to do a thing, now tell me how to do the thing.”
  * Every project benefits from every example that you write.
  * How do I do it, I need to change this thing, how do I do it with that plugin that you advertised that you support, right?

> _**"I need an example and then I need some more examples, as well as straight-up library documentation, generated code, whatever is working in your local space."**_



### Installable Item README

* Requirements 
* Installation instructions, 
* Usage instructions. 

> _**“Click to deploy -- Heroku, now you have a public URL, use it here, has worked really well for us. And allows users to use tools that we’ve made, or try approaches that we’ve put together for them really, really easily.”**_

* Deployment instruction, 
  * More than just running it locally. For something that is supposed to be a standalone project, it’s really important, this is often completely missing as well. 

> “_**For us, this is proven to be the hardest step, because we’re in dev rel, so we don’t have a lot of our Obs engineers hanging around, so this can be a bit of a challenge. And it’s one that we’re just going to keep on working on. It’s not the easy thing, but it’s the right thing.”**_



###  Supporting Code README

* Don’t have a lot of rules about what must be in the readme for this. In fact, the focus should be to link to the thing it is for.
* So you make the sample code, you write the blog post. 
* The linking thing, where you make one thing and then you make another thing and you link to it? It’s really hard to link back to the first thing, but there are lots of places where it’s really important.

> _**“We discovered that if you landed on our reference pages, either rendered on our docs portal, or you just grab the spec because that’s what you do with open API specs. There was no link to the actual documentation for this. So look out for traps like that, it’s super easy to do between artifacts. Between your blog posts and your repo, or whatever. So, look out for it.”**_

### README Extra Info

How to get help?

* How would you like people to ask for help? Should they open an issue on GitHub? 
  * Would you like a particular tag to have an overflow? Does your organization run an online forum?
* Giving the next steps. 

###  Beyond the README

  
Readme is really important, it’s a great place to start, but there are other things that we can do to make our repositories both more welcoming but also more discoverable. 

* _**Getting the metadata right on your repository**_ 
  * Please give your project a clear name.
  * It’s super important to use the tags, GitHub calls them topics
  *  Don’t skimp on the description. 
    * It’s shown here and it’ll be shown in search results. 
    * People might not be seeing the whole page. It’s not the bit that goes before the files and people are reading it there and then the readme. 
* _**License**_
  * If you want people to interact and use your open source stuff, it needs to have one.
  * There’s no point in creating a thing without documentation and there’s no point in publishing open-source code without a license. “A real one, an OSI approved on, not something you made up.”

####   Welcome participation 

Giving permission and then actually welcoming use are two different things. 

* **codeOfConduct.md**
* **contributingFile.md**

…._**are two things that really enable users to have confidence in being part of your project as users, as contributors.**_ 

* Think about what this means to you and your team. 
* If you have a violation, who’s going to deal with that? Who’s going to support that user? And who’s gonna, like, what’s the outcome? Write that down, make sure that exists. ‌

> _**“Don’t let users engage with your project and then tell them no thanks. We have a couple where our contributing file just says “We don’t accept patches.” “ Be clear if you don’t want the users involved."**_

