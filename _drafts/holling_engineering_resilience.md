---
author: Reed Porada
date: Jun 14 2017
title: Review of _"Engineering Resilience versus Ecological Resilience"_
---

## Bibliographic Information
C. Holling. Engineering resilience versus ecological resilience. Engineering Within Ecological Constraints, pages 31–43, 1996.

http://jimgray.azurewebsites.net/papers/thetransactionconcept.pdf

## Summary

In this paper Holling attempts to highlight and draw a difference between engineering and ecological resilience. The argument is based on the view that the objectives of these two forms of resilience are different. While they both are trying to create resilience, Holling states that engineering resilience focuses on desires for fail-safe design, and ecological resilience looks for safe-fail designs. This is not too dissimilar to the fail-closed and fail-open argument, but there is a difference. Fail-safe attempts to avoid failure and when it occurs prevent harm. Safe-fail acknowledges failure will occur, but attempts to prevent catastrophic failure when it does occur. Put more directly by Holling: engineering resilience focuses on efficiency of function while ecological resilience focuses on maintaining the existence of function. This I believe is one of the more relevant points to cyber security. 

## Managing for Engineering Resilience

The synopsis by Holling for ecological systems where humans have typically attempted to manage "the result is that the ecosystem evolves to become more spatially uniform, less functionally diverse, and more sensitive to disturbances that otherwise could have been absorbed." This seems like a phenomenom that we see in information assurance, and maybe even computing in general. First, to manage the complexity of a computing environment we tend move towards homogeneity and uniformity in our deployments. With an active unpredicted disturbance, this means that we have limited capacity to absorb that. While this concept seems to ring "true" for our engineered systems, I am not sure that we have a naturally occuring diversity that exists in nature. It seems to depend on where you draw the abstraction lines. For example we had many different types of processors, and eventually we became dominated by the x86 architecture. What I am not sure about is this really different than the endo vs exothermic temperature regulation argument. The better related abstraction to thermal regulation is probably in regards to the Von-Neumann architecture versus the Harvard architecture. This would make x86 versus ARM the equivalent of different ways to internally regulate temperature. 

The other aspect that I struggle with is does the limited diversity we have really have resilience. Meaning while people argue for diversity of platforms, and so forth, do we really have sufficient variance in that diversity to be reislient. The push against diversity within IT infrastructure seems to be in direct response for the goal of engineering resilience. We want efficiency, constancy, and predicability. Within the IT infrastrucutre we create standards and interfaces to achieve these particular goals. Are they in conflict with the goals of ecological resilience that looks for persistance, change, and unpredictability. 

Let's look at ACID (Atomicity, Consistency, Isolation, Durability) and databases. This seems to encompass at some level the constructs of both forms of resilience. The transaction concept was mostly for aiding in the creation of a consistent **<TODO: COME BACK TO THIS Espeically after Matt's Talk link>**

> "In the examples of resource management that I have explored in depth, not only do ecosystems become less resilient when they are managed with the goal of achieving constancy of production, but the management agencies, in their drive for efficiency, also become myopic, the relevant industries become more dependent and static, and the public loses trust."

Have we seen the realization of the above observation in computer security? With the regulation to the NIST RMF do we see less creativity? Increased dependence on the model, and tools, and overall less resilience in our systems? I know we have definitely lost trust in our systems. One of the goals of the utilization of the RMF is to enable reciprocity. Reciprocity in DoDI 8500.01 (2014) "reduces time and resources wasted on redundant test, assessment and documentation efforts." Those benefits sound a lot like the "goal of achieving constancy of production." We are also seeing people become myopic about cybersecurity as a result of these management objectives. It is this observation that makes the Holling paper relevant to me. He has identified a behavioral tendency in the management of complex systems by man that is representative of what is being seen in the management of cybersecurity infrastructure.

Another observation by Holling on previous management efforts: "That is, the short-term success of spraying led to moderate levels of infestation and partially protected foliage that became more homogeneous over larger areas, demanding ever more vigilance and control." Two parts to this observation that I resonate with. First I think a similar observation about the behavior from utilizing something like HBSS is seen. It can be similar to spraying. By spraying we reduced the opportunity to remove underlying problems, and we have also created a new attack surface that is more uniform and requires even more vigilance and control over. The second aspect was that just as was the case with spraying we felt that we had created a better situation, but in reality we created a much more fragile system. Our myopic view of the time has led to disastrous effects in the long term. This si a short versus long-term view issue. Are we better off not having host based defenses and encouraging/enforcing the system to adapt and evolve, or are we better off with the short term protection of AV and a stagnant homogeneous vulnerable system?

> "The heart of these two different views of resilience lies in assumptions regarding wheteher multistable states exist. If it is assumed that only one stable state exists _or can be diesgned to so exist_, then the only possible definitions for, and measures of, resilience are near-equilibrium ones--such as characteristic return time. And that is certainly consistent with the engineer's desire to make things work, not to make things that break down or suddenly shift their behavior. But nature is different"

For a software system what would multiple stable states look like? Is this something akin to the asynchronous computation from Sutherland? Or the partial, but always provided answers type system?

## Managing For Ecological Resilience
> "I conclude, therefore, that reduction of variability of living systems, from organisms to ecosystems, inevitably leads to loss of resilience in that part of the system being regulated."

What are the implications of that conclusion on how we regulate information systems?

> "It is overlapping 'soft' redundancy that seems to characterize bilogical regulation of all kinds. It is not notably efficient or elegant in the engineering sense. But it is robust and continually sensitive to changes in internal body temperature. That is quite unlike the exmaples of rigid regulation wehre goals of efficiency gradually isolated the regulating agency from the things it was regulating." 

This last part is what has me thinking about how through our regulation we have removed the agency of the various organziations to work through and solve their own problems. By being so prescriptive in outputs we have removed diversity within our systems.

> "That is the heaart of the role of functional diversity in maintaining the reslience of ecossystem structure and function."

Operating system and application diversity are equivalent to species diversity not functional. Functional diversity would be the equivalent of using two different methods for calculating a result. How often is this latter strategy utilized?

> "Such diversity provides great robustness to the process, and as a consequence, great resilience to the system behavior"

> "Variability is therefore not eliminated. It is reduced in one place and transferred from the animal's internal environment to its external environment as a consequence of allowing continual probes by the whole animal for opportunity and change. Hence the price of reducing internal resilience, maintaining high metabolic levels, and operating close to an edge of instability is more than offset by that creation of evolutionary opportunity." 

> "...operating near an equilibrium far from an instability defines engineering resilience."

> "It requires flexible, diverse, and redundant regulation, early signals of error built into incentives for corrective action, and continuous experimental probing of the changes in the external world"

Is this where chaos engineering and SRE are headed? Do they help create fleible, diverse and redundant regulation? Do they encourage help ensure there are early signals of error? Does the culture that adopts these practices provide incentives for corrective action? Can one frame chaos engineering as a continuous experimental probing of change in the external world?


## Conclusion 

> "The scientific understanding of the natural system becomes more integrated, and the issues themselves are not posed in response to needs to maximize constancy or productivity of yield, but to ones of designing interrelations between people and resources that are sustainable in the face of surprises and the unexpected"


## ToDo
* Relate this concept to how the DYN attack was absorbed
  * To how there were failures in the infrastucture (single DNS servers or resolvers)
* 

