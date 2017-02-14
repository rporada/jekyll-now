---
layout: post
title: Understanding Context and Change
tags: first
category: 
  - practice
  - security
author: Reed
---

## A Story: Garages
Why do we have garages? 






Some people may answer that question with to protect our cars from the elements. That would be the dictionary definition. Maybe a different question: What do we do with our garages?

* Protect vehicles
* Protect lawn equipment
* Store sports equipment
* Temporary workshop
* Extra storage space
* ...

Garages thus began as protection from the weather for our vehciles, from carriages to automobiles. Overtime we added additional roles: entrance to our house, lawn equipment storage, and workshops. 

Let us look at an element of the modern garage: the door. Garage doors have changed over the years. Early garages may not even have a door. The door was added to provide full protection. Over time we automated the opening and closing with door openers. Openers made it easy to open and close heavy doors. We then added remotes to the openers to allow us to stay in our vehicles while opening and closing doors. 

There were problems with remote openers. Early openers were audible or infrared. The problem was revealed in dense neighborhoods. Your door opener would also open up the neighbors door opener because they were not uniquely coded. Garage manufacturers added rolling codes to door openers. This reduced the likelihood of opening your neighbors door, or opening an arbitrary door. They further specialized and had openers paired to remotes, making the sequence unique to each opener and set of remotes.

Now take a look at garages from the perspective of a home thief. When garages were detached and typically in the back of a home, they were a good target because of being obscured. However, they only really housed a car. So the time to break-in was based on if a vehicle was present. Overtime garages migrated to adjoin the house, and entrances through the garage into the house were added. People also began storing more things in the garage making. Now breaking into a garage had more value and opportunity.

Breaking into a garage always had potential challenges. When there was no door, there was no problem. When doors were added, people also added locks to the garage doors. This hindered access. Remote openers changed a few things, at first a thief could just get a remote and potentially was able to open any garage. Rolling codes made this more difficult, and unique coding made it even more difficult. These "features" of openers became advertised as security features. 

At the time of the addition of these security features, it was reasonable to call them that. When added it was known that a naive rolling code scheme is vulnerable to brute force, and to a replay attack. However, at the time the hardware necessary for that was expensive, thousands of dollars. It may also take a long time to be able to execute these attacks. The threat model fixed the adversary at these points, and the schemes were deemed sufficient.

Fast forward to 2015. Software defined radios have made it possible for a few hundred dollars to build a really nice system for analyzing the RF spectrum and generating signals. With a little knowledge, one is able to develop a replay attack and the accompanying hardware for approximately $30 [^1]. Now, the thief has a cheap and reliable attack to what has become a valuable target. The ball is now in the homeowner and door opener manufacturers court.

## Observations from the Story

### Fixed Model and Assumptions

### Changing Context and Environment

What about non-domestic garages? Does this equation change?

### Ability to Respond


---

[^1]: see [Rolljam attack](http://makezine.com/2015/08/11/anatomy-of-the-rolljam-wireless-car-hack/)

[^2]: [Physical garage attack](https://www.schneier.com/blog/archives/2010/08/breaking_into_a.html)

[^3]: A description of the importance of context when being asked to compare (src: [Kottke](http://kottke.org/17/02/maybe-theres-more-that-brings-us-together-than-you-think)):
<!-- > From Amos’s theory about the way people made judgments of similarity spilled all sorts of interesting insights. If the mind, when it compares two things, essentially counts up the features it notices in each of them, it might also judge those things to be at once more similar and more dissimilar to each other than some other pair of things. They might have both a lot in common and a lot not in common. Love and hate, and funny and sad, and serious and silly: Suddenly they could be seen — as they feel — as having more fluid relationships to each other. They weren’t simply opposites on a fixed mental continuum; they could be thought of as similar in some of their features and different in others. Amos’s theory also offered a fresh view into what might be happening when people violated transitivity and thus made seemingly irrational choices.
> 
> When people picked coffee over tea, and tea over hot chocolate, and then turned around and picked hot chocolate over coffee — they weren’t comparing two drinks in some holistic manner. Hot drinks didn’t exist as points on some mental map at fixed distances from some ideal. They were collections of features. Those features might become more or less noticeable; their prominence in the mind depended on the context in which they were perceived. And the choice created its own context: Different features might assume greater prominence in the mind when the coffee was being compared to tea (caffeine) than when it was being compared to hot chocolate (sugar). And what was true of drinks might also be true of people, and ideas, and emotions.
> 
> The idea was interesting: When people make decisions, they are also making judgments about similarity, between some object in the real world and what they ideally want. They make these judgments by, in effect, counting up the features they notice. And as the noticeability of features can be manipulated by the way they are highlighted, the sense of how similar two things are might also be manipulated. For instance, if you wanted two people to think of themselves as more similar to each other than they otherwise might, you might put them in a context that stressed the features they shared. Two American college students in the United States might look at each other and see a total stranger; the same two college students on their junior year abroad in Togo might find that they are surprisingly similar: They’re both Americans!
> 
> By changing the context in which two things are compared, you submerge certain features and force others to the surface. “It is generally assumed that classifications are determined by similarities among the objects,” wrote Amos, before offering up an opposing view: that “the similarity of objects is modified by the manner in which they are classified. Thus, similarity has two faces: causal and derivative. It serves as a basis for the classification of objects, but is also influenced by the adopted classification.” A banana and an apple seem more similar than they otherwise would because we’ve agreed to call them both fruit. Things are grouped together for a reason, but, once they are grouped, their grouping causes them to seem more like each other than they otherwise would. That is, the mere act of classification reinforces stereotypes. If you want to weaken some stereotype, eliminate the classification. -->