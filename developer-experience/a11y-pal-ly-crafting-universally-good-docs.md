---
description: >-
  Google’s Sangeetha Alagappan talks about making your docs inclusive, what
  accessibility means in the context of documentation, and common pitfalls you
  might encounter.
---

# A11y pal\(ly\)- crafting universally good docs



{% embed url="https://youtu.be/v\_jouD0A\_iI" caption="Video" %}

## Summary:

* Accessible solution delights when it blends into the product ecosystem, and it provides the user with all that they need but is still personalized to their particular abilities. 
* You should be cognizant of how you create things. You should think outside the box. 
* Accessibility is all about being creative and being surprised and just being human.
* Write style guides. 
  * Where when you set up a style guide for how you want your documentation to be, 
  * It’s not only a mission statement where you tell others what you want your documentation to be, but it’s also a roadmap to show people how to get there and hold them accountable. 
* **Disabilities and docs** 
  * Low vision
  * Colour vision deficiency 
  * Blindness
  * Motor disabilities
* **Common problems** 
  * Lack of alternate text and or equivalents.
  * Colour contrast
  * Unnavigable by keyboard

## Scribbles:

### Accessibility

* Let’s talk about accessibility and what that means for documentation. It might be a noble cause to invest in accessibility, but it’s also an incredibly selfish one because it’s an investment in your own future,
* Because everyone will be temporarily or permanently impaired at some point in their life, and that’s according to the World Health Organization, who are very sprightly people.
* Accessibility Isn't a zero-sum game.
* Everybody wins when you invest in accessibility. 
* If national well-being and prosperity and societal harmony is not enough for you, accessibility also reaps economic benefits. 
  * Example - Over 15% of the world have a disability. 71% of them leave an inaccessible site immediately, and very recently it’s also been a great pot for lawsuits because there’s a lot of money in that.

‌  


### Disabilities and docs 

* When we talk about documentation, we talk about a narrow scope of disabilities because it is a very particular interaction that users have with documentation and product interfaces. 
* Users with low vision, so moderate to severe impairments, colour vision deficiency, mostly red-green colour blindness. 
* Users with blindness, who are more likely to use screen readers. 
* But we also talk about temporary disabilities, like changes in the device, age, situation, technical infrastructure, and temporary situations, which are not necessarily disabilities, 
  * Noisy train, 
  * You’re always one-handed and you’re trying to use a device with the other. And 
  * On the rare sunny day in London, that one day where it’s too bright to see your screen. 

‌

### Common problems 

* What we see in the documentation that makes it inaccessible is the lack of alternate text or text equivalents. 
* If a user can’t depend on visual stimuli, you need to give them an alternate text, because it gives them context 
* Or alternatively, if you don’t use all text, you can prepend an image with all of this information so that it sets the context nicely.
* Use correct colour contrasts. 
* Having every part of your documentation navigable by keyboard.
  * Everything has to be reachable with tabs.
  * Your left and right and bottom keys, your enter key. It’s always important to check if it can be navigated by the keyboard.
* State indicators. 
  * If this were an error message, you wouldn’t be able to tell if it was red or green if you had red-green colour blindness. 
  * So, the idea is to not rely on just one visual cue. 
  * You should have multiple different cues, like an image with alt text that tells you that’s an error or an error text message. 
  * You also shouldn’t obscure information when you’re asking a user to input something.‌

### Case study 1: Bbc iPlayer

* A couple of years ago, BBC looked at their iPlayer, the home of all your favourite shows that everybody seems to have watched and can’t stop talking about. 
* They realized that there were a lot of accessibility problems with the current interface.
* Mostly, that TV and radio are such broad categories, but that’s what’s on the top bar.
* Anybody who’s navigating it by keyboard had to go through everything to get to that. 
*  If you’ve ever actually used a screen reader, it’s incredibly infuriating because it reads out everything. 
  * Unless the page is structured minimally and optimized for a user workflow, it’s going to read out every single thing on this page. 
* The keyboard behaviour was not intuitive, so just pressing right or left, you couldn’t tell predictably where the cursor would go. 
* So they took all of that information and all of the insights from their user studies, and they realized that users require three things. 
  * They need to be able to search for what they’re looking for. 
  * They made it easier to scan a page and they added search functionality. 
  * Broader categories that people could go to the right on the top, like channels, categories, A to Z, TV guides, so you could format how you wanted to consume this information. 
  * Saving favourites.

### Case study 2: Trello

* If you use any sort of project management tool, like Canva and all of these things, it’s essentially the ability to put things into to-do lists.
* Trello realized that when you have coloured labels, it’s kind of hard to tell if you don’t have colour. 
  * They added a colour-blind friendly mode
    * You can add patterns to the edges of your labels so that you can differentiate it even if there’s no colour. 
    * The response to this on Twitter was actually incredibly positive, which if you’ve ever been on Twitter, is almost a miracle.  

### Case study 2: NPR

* Public radio, NPR. 
* They’ve gone and looked at all of their podcasts, and they’ve transcribed all of them so that there’s a text equivalent for all of their podcasts. 
* And then they went and looked at their metrics as all good engineers and designers do, and they realized that their search traffic increased by 6.86%. 
* Their unique visitors increased by 7.23%. 
* There was an increase in inbound links and search visibility.
* They had increased SEO and keyword visibility. 
* Visitors who were in sound-sensitive environments or noisy environments were able to still consume podcasts. 
* As a result, they had a wider reach. 
  * They have a bigger market when you’re able to because now they can easily translate their content to other languages. 
  * They were able to enable search on all of their podcasts. 
    * You could search text and it would reference a specific section of the audio on a podcast.

‌

### How should you write?

* How should that affect how you write and create documentation and products as a whole? 
* You should respect the semantics because of native HTML tags like image, caption, table. 
* Always prefer the native HTML tags over custom ones that you build yourself. Don’t bury context. 
* Be upfront, summarize your intent.
* Have multiple cues, don’t rely just on one visual cue, like colour or geographical location. 
* Most importantly, write with empathy. 
  * You should approach the experience as a user. 
  * You should create personas.
  * You should test edge cases‌.

Quote “accessibility’s an incredibly human discipline. You should also approach it in an incredibly human way.”  


#### Documentation, the architecture and the hierarchy 

* Navigation tree tells you what your journey is going to look like. 
* That’s very important for screen reader users because they just need to know where to go to get what they need. 
* Always make sure that the way you use headings is consistent because that also helps screen reader users because they don’t have the visual context. 
* You should always set rules like H1 should be top-level tags, H2 should be subheadings, and you should have a guide of how you use elements. 
* You should label with context and care. 
* You should label it in a way that is sufficiently descriptive. 
* Sometimes when you write alt text for images, it doesn’t sufficiently convey what the image is.
* You should also test a common workflow because that’s the only way you know how a product works. 
* You should go and replicate the user workflow. 

‌

#### Advocate for UI improvements

* If you see something, you should say something. 
* To iterate once again, you should write with empathy.

