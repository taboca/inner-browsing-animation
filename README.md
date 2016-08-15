## Introduction

New design to support sectioning animation  - the concept in which 
cinematographic animation techniques may govern how a series of elements
will be presented as they are part of a same section

In the current architecture, all 'slides' are elements that are presented uniquely, i.e. based in rules that are applied individually to each slide element. This means that the author can define effects that
will govern, for example, how a given slide will enter the scene — think of a transition. 

Another kind of effects can be define as part of the slide kind, such as when you have a given slide
which has a number of inner elements. 

The above model does not take in consideration the possibility of more dynamic aggregations to be composed based in dynamic rules. To illustrate an example, think about a kind element, an author. If new authors comes into a presentation, would it be possible to showcase the "best authors?"

A proposed solution is to support presentations to allow the existence of category-elements, such as author; and beyond that, to enable new section supervisor elements to define how choreographic rules may apply for a given range of category-elements. 


