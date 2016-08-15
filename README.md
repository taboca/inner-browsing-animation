## Introduction

The goal of this work is to support the design and development for a technology that is aimed to enhance models for animation design and choreography. In the short-term, the aimed outcome is to define cinematographic animation techniques that may apply and govern how a series of incoming elements will be presented as they become part of given group of elements. 

### The case for slides system 

We will use the story of slides as an attempt to organize the problem, therefore to have a direction for a solution. First, imagine a traditional animation experience for a presentation system. Say it's an animation authoring system for presenting slides. In such system, all 'slides' are elements that are presented uniquely, i.e. based in rules that are applied individually to each slide element. This means that an author can define effects that will govern, for example, how a given slide will enter the scene. An example of an animation that applies to a slide is a transition. 

Another kind of animation effect could be defined within the slide. As an example, an author may want a slide that displays a series of items that needs to be shown in a given order. For an author, these elements are considered as sub-parts of the slide. 

## Understanding relationships among elements

The above examples show that relationship among objects is critical to define storytelling features such as transitions — among slides and also for the case of the inner items. This is really clear in the second scenario. As all items are clearlyh sub-items, we normally expect display techniques to be the same for each item. If a professor wants to list its passions, it is likely that each item will be presented using a same presentation technique. This could be as simple as an item that is shown with no effects or it could involve animation, such as when each item is shown with a fade in effect. 

Animation effects, or transitions, of the same kind, can also be used in scenarios among slides, however. Think of the first scenario but assume that each slide is an item of a same category. Say you have a presentation like the following: 

```
Title: The animals that I love

Slide 1: lion

Slide 2: tiger

Slide 3: eagle
```

While the above is not a one-slide list, with 3 elements; yet it displays a condition of structing the inner elements. Therefore, the transition between slides could well be organized with the same effect — say a fade in for every time you slide towards a new animal. 

The usage of the same transition, to indicate that you have a new "animal" kind, becomes a cue for an observer audience. Say that you are watching a presentation with a series of animals and you never know what is the amount of animals to be presented. Would it be possible to know when the list ends before seeing the actual slide totally shown? 

If the transitions are the same, it would; but not exactly because you can see a hint of the next animal as it comes. In part that is true. But it is also true that the transition effect becomes an indicator of the "next item". This is not much different of the structure that helps you know a new item when a bullet is shown in time: 

## List 

* New item 
* New
* N

The case of the "unknown" number of animals is an example of a dynamic aggregation — if you look at it from the perspective of tha audience. We dive into this case because our focus is understand different modes of choreographic experiences can be used to organize animation for elements that needs to be presented. 

## Initial design 

A proposed solution is to support presentations to allow the existence of category-elements, such as author; and beyond that, to use section supervisor elements to define how choreographic rules may apply for a given range of category-elements. 


