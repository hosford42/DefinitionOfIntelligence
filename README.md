NOTE: This is a work in progress. This repository is not a code repository, but rather a place for me to record and share my ideas.

# Definition of Intelligence
*A definition of intelligence, intended to be sufficiently concrete to support implementation efforts (i.e. Strong AI)*

## What is intelligence?

There has been a lot of debate over what the term *intelligence* actually means, particularly in the Artificial Intelligence community. To date, this concept has presented something of a moving target, as efforts towards implementing AI repeatedly demonstrate the distinction between *cleverness* and *intelligence*. Many definitions proposed to date are too vague to offer much guidance to the prospective engineer of "strong" AI -- sotware that can actually perceive and reason about the world with a flexibility roughly on par with human beings.

Merriam Webster provides [several relevant definitions of intelligence](https://www.merriam-webster.com/dictionary/intelligence) which might serve as starting points:

* "the ability to learn or understand or to deal with new or trying situations"
* "the ability to apply knowledge to manipulate one's environment or to think abstractly as measured by objective criteria (such as tests)"
* "the act of understanding"

The last definition above is the most telling one. One of the key distinctions often pointed out between the capabilities of human intelligence and that of modern AI software, particularly Deep Learning, is the inability of AI software to transfer its capabilities to new domains. The most brilliant chess AI cannot even *process* a checker board layout, much less attempt to play a decent game. This is because the AI does not *understand* chess or its relationship to games in general; rather, it is just extremely clever at optimizing a strategy within the framework spoon fed to it by the developer.

# What is understanding?

What does it mean to *understand* something? Understanding a system requires a person to hold a *model* of that system within their mind, which can be used, among other things, to reason about the system, to plan interactions with it, to make predictions about it, to design experiments to gain new insights about the system, to compare the system to other systems, or even to translate effective strategies from one system to another. (Note that the word "model", as I use it here, has a very different meaning from the word as it is commonly used in the domain of machine learning.)

It is this ability to develop, maintain, and use models, I propose, that sets apart human intelligence from so-called "narrow AI".

## What is a model?

The idea that intelligence is about understanding, and that understanding is about modeling, is an illuminating one, but we cannot leave it at this, because the term "model" has yet to be defined clearly. What makes something a model of another thing? What properties must a model possess for us to comfortably say that understanding is actually taking place?

A model is a system whose behavior mirrors that of another system. In mathematical terms, the model is (approximately and conditionally) isomorphic to that of the system being modeled. There are a wide variety of modeling approaches, but what is universally present is that the salient relationships between components of the modeled system are also present between the corresponding components of the model. We can use the model to make inferences about the system it models, because the model's moving parts move in a similar way to that of the original system.
