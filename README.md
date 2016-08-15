## Introduction

In this work, my goal is to support the design and development for a technology that is aimed to enhance models for animation design and choreography. In the short-term, the aimed outcome is to define cinematographic animation techniques that may apply and govern how a series of incoming elements will be presented as they become part of given group of elements. 

### The case for slides system 

We will use the story of slides to expand the problem and attempt to organize the problem, therefore to have a direction for a solution. First let's imagine a traditional animation architecture for a presentation system. Say it's an animation authoring system for presenting slides. In such sytem, all 'slides' are elements that are presented uniquely, i.e. based in rules that are applied individually to each slide element. This means that an author can define effects that will govern, for example, how a given slide will enter the scene. An example of an animation that applies to a slide is a transition. 

Another kind of animation effect could be defined as part of the kind of slide. As an example, an author may want a slide that has a series of items that needs to be shown in a given order. For an author, the elements may be considered as sub-parts of the slide — like a slide being a theme. 

## Searching for relationships among elements

In the above model, we have a notion that relationship is very important both for the case of the transition or the case of the inner elements that needs to be shown for a given slide.  does not take in consideration the possibility of more dynamic aggregations to be composed based in dynamic rules. To illustrate an example, think about a kind element, an author. If new authors comes into a presentation, would it be possible to showcase the "best authors?"

A proposed solution is to support presentations to allow the existence of category-elements, such as author; and beyond that, to enable new section supervisor elements to define how choreographic rules may apply for a given range of category-elements. 


