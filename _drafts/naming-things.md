---
layout: post
title: "Naming things"
date: 2021-06-18
tags: C# Naming OOP
excerpt_separator: <!--end_of_excerpt-->
---
Is quite hard, they say. And I agree.
Often times I struggle coming up with a name for a variable, method or class that I feel properly describe the thing.
But don't let your self surrender and just use stupid names.
<!--end_of_excerpt-->

## Why is naming important.

Naming is important for several reasons, the most basic one is telling things
apart from each other. But it also indicates *intention* and *use*.

By *intension* here I mean what you intend the thing to represent and there 
are good reasons to look into DDD and ubiquitous language here. I will not go 
deeper into that topic than to say that it helps if names are the same in
software as it is in the real world. So that stake holders and developers
use the same language for the same thing.

Being descriptive in naming is more important than using short names. It is
better to thoroughly describe a thing than to make up acronyms for everything.
This reduces the risk of confusion.

By *use* I believe it to be important to describe how a thing is supposed to 
used by hinting it in the name. For example it should be obvious that a data 
transfer object (DTO) actually is a DTO.
And grouping DTO's also helps me find what I'm looking for.

## Introduce named methods in place of logical expressions
Closely related to naming is, in my opinion also breaking out blocks of code 
or small expressions into subroutines.
