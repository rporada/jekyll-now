---
layout: post
title: Introducing Security Thoughts 
tags: first
category: introduction thoughts
---

Over a decade of researching computer security has brought me to this point. Starting a blog.

Over the last ten years I have worked on testing, vulnerability discovery, and system architectures. More recently, I have been researching the history of computer security[^1], and trying to understand how we have progressed. Seeing little progress, I have branched out to other areas. These areas include: systems theory, control theory, social science, and psychology. This blog will cover these various topics, how they interact, and how we can learn from other disciplines to improve security. 

I hope you enjoy.

A few other notes as this journey begins. 

I will not often use the term _cyber_. I do not find it to be a generally useful term when describing security. The current use of the term does not clarify what is being discussed. However, if I am using it on this blog it is in the context of the origin of the word and its use in cybernetics that is different.

> __cybernetics__ (_noun_) -- the science of communications and automatic control systems in both machines and living things

Cybernetics was a term used in control theory by Norbert Weiner and Ross Ashby among others. They took the term from the greek term kubernetes.

> __kubernetes__ (_noun_) -- steersman

If _cyber_ is used in the context of cybernetics, then cyber security is the property of feeling _safe_ about the control of your system(s).

This brings me to the second definition, that of security. For many in information security the security can be defined as having _confidentiality_, _integrity_, and _availability_. The so-called __C-I-A__ definition. While, in some cases I believe these three things may provide security, I do no think they capture the true state of things. Simplifying to these three things is dangerous. It makes it seem _easier_ than it really is. Using this principle also reduces the context and allows for ambiguity. 

For the purposes of this blog, security is viewed similarly to how Christopher Alexander in _Notes on the Synthesis of Form_ looks at design problems:

> ... every design problem begins with an effort to achieve fitness between two entities: the form in question and its context. The form is the solution to the problem; the context defines the problem. In other words, when we speak of design, the real object of discussion is not the form alone, but the ensemble compromising the form and its context. Good fit is a desired property of this ensemble which relates to some particular division of the ensemble into form and context.

I prefer this perspective for two reasons. One it implies that one cannot judge the form, or the system, in isolation. I believe this is true of any security product or solution. It is not possible to evaluate the goodness of a solution without understanding the bigger context[^2]. The second point from Christopher Alexander's view is that of fitness being a _desired property_. In my view, security is also desired property of a system[^3]. It is not a technology, and not something that can simply be added on. A property is also malleable. As the context changes, the _goodness_ of the property changes.

With those definitions, I hope my view on security is a little clearer, and I expect it will continue to evolve as it has over the last decade.

---

[^1]: Two notable reports on security are the 1970 DSB report [Security Controls for Computer Systems](http://www.rand.org/pubs/reports/R609-1/index2.html) and the report from Cyber Command Historian Michael Warner [Cybersecurity: A Pre-History](http://www.tandfonline.com/doi/abs/10.1080/02684527.2012.708530?journalCode=fint20) 

[^2]: Context in my view includes the system in which the solution is being applied, and the purpose, operation, and life-cycle of said system. I also look beyond the technical and include social aspects to the bigger system. These include the people, processes, and policies that govern the use of the technical system. 

[^3]: In future posts, I expect to explore this concept further. I believe it is not just an _ility_ or a desired property, but an emergent property from the ensemble of the form and the context.
